stamplay-tutorials - 03-landing-page-form
========================================

See how to use the Stamplay Form API to submit a form entry.




-----------------------

## Using the example

For using this example you have to:

* Create a Stamplay app
* Add form component and configure it
* Upload the application's files

## Create a Stamplay app

Go to [Stamplay Editor](https://editor.stamplay.com/) and create a new application.

## Add form component and configure it

Define a form schema for this app, we will define the landing form as follows:
### Settings 
* One entry per user : false
* Only logged user : true

### Landing form
* Name: **email**, Type: **string**, Required : **true**

## Access your data
You can access to the form entries via API at :

<<<<<<< HEAD
* https://0b2a06.stamplay.com/api/form/v0/forms/landing-form/entries
=======
* https://4a2b94.stamplay.com/api/form/v0/forms/landing-form/entries
>>>>>>> 34dbc64b0eb18ad29856087c527125b04d2643c7

or if you are creating an app:

* https://APPID.stamplay.com/api/form/v0/forms/FORMID/entries

## Upload the application's file

In order to start clone this repository :

    git clone git@github.com:Stamplay/stamplay-tutorials

Or download it as a zip file
	
	https://github.com/Stamplay/stamplay-tutorials/archive/master.zip 

 upload the frontend files of this example in your app and you can do it in two ways:

* Copy/Upload them via the Layout section of your app on Stamplay editor
* Get Stamplay Sync on [OSX](http://cdn.stamplay.com/stamplay-sync/mac/stamplay-sync.zip) or [PC](http://cdn.stamplay.com/stamplay-sync/win/stamplay-sync.zip) and run it. Make it download the frontend assets of your app and then replace them with the ones you got from this repo. Stamplay Sync will upload everything for you on your app.

