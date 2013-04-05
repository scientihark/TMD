------------------------TMD-------------------
----Text MarkDown For API documentation

----Please copy and paste or open this readme.md In TMD_Reader!
-----------------------------------------------

#Title=Document For TMD & TMD Reader
#Project=Project TMD
#API Level=1
#Version=2013040401

#:Useage

#For TMD for example

~JSON:POST:False:False

@Request
email.|.true.|.string.|.Email
uname.|.true.|.string.|.UserName
upass.|.true.|.string.|.UserPass
re_upass.|.true.|.string.|.Confirm
utoken.|.true.|.string.|.ClientSide token
captcha.|.true.|.string.|.Captcha
@End

@:code
{
        "flag": "ok",
        "data":{
        	"user": {
                  "uid": 1,
                  "stoken": " gzdvbrvb24rtgaw4rg4t",
                  "uname": "zt",
                  "info": {
                  	"addr":"a dr."
                  },
                  "point": 1
        	}
        }
    }
@code

@Return
flag.|.string.|.ok/error/error info
data.|.object.|.Pubilc Data Object
@End

@:notice
Then the File should be put In the TMD reader ,go and have a try !

Here is desktop App for windows user .we build it with LibCEF and packed it with Vmware ThinApp
have fun!~~
@notice



