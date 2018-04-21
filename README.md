# make simple awesome chrome_extension:

# as google chrome extension procedure:
   first, make a file named menifest.json
   
# add these in json file, these are recommanded:
   {
    "manifest_version" : 2,
    "name" : "linkin",
    "version" : "1.0.0",
    "description" : "follow these links & stay connectd",
    "icons": {"128" : "r_128.png"},
    "browser_action" : {
        "default_icon" : "r_19.png",
        "default_popup" : "index.html"
    },
    "permissions" : ["activeTab"]
}

  for more information: search "chrome extension menifest"
  
 # create a html file what we want to do.
 # we can create any js file if need.
 # go to chrome seetings->more tools->extensions->enable developer mode;
 # click load unpacked.
 # show the folder
 # finish
 
 # if we want to publish extension:
    follow the link: https://developer.chrome.com/webstore/publish
    click chrome developer dashboard
    upload the zip file
    read the instructions
    pay $5.00
    publish it
  
# finish  
