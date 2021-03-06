# Yourls-Email-Notify
Have Yourls send you an email when someone clicks a shortened link.

This plugin is very easy to configure.  Simply add the following info to the "Click Notification Email" admin page:
* To Email Address - this is where you want to receive these notification emails.
* From Email Address - this is the address you want the emails to be sent from.
* My IP File (optional) - this file contains your IP address.  It's used to compare to the visitors IP so you can see which clicks were made by you.
* Bots File (optional) - this file contains a return delimited list of bot names that you don't want triggering the email.
* Error Log (optional) - path of an error log for testing, in case you have a problem with this script.
* Log Errors? - choose "Yes" or "No" depending on whether you want to log errors or not.  Choosing "Yes" requires a log path in the Error Log field.

Plus, if you don't mind digging into the code, you can customize the generated email to your heart's content!

### Installation Instructions

1. Copy everything to your YOURLS_DIRECTORY
2. Visit the "Click Notification Email" admin panel to customize your install

#### Caveats

* This plugin is really only useful for sites that have a low volume of clicks and you need to know when the recipients click on them.  Example: say you have an e-commerce site and you need to send links to your customers for quotes or other important information.  This plugin allows you to know when/if your customer clicks on that link so you can take the appropriate action.
