# microsoft-teams-bot
bot to attend online class

## Configure

There are few things you need to configure before running this bot.

 - Open Microsoft teams on your browser, login to your account, change the dashboard view to list view (from grid view), so that your classes are displayed in a list view. 

 - Open *bot.py*, and put your microsoft teams credentials in the **CREDS** dictionary. 
 - Example - `CREDS  = {'email' : 'myemail@email.com', 'passwd':'''mypassword'''}`
 - Open *discord_webhook.py* and put your discord webhook URL in the **webhook_url** variable. 
 - Example - `webhook_url = "https://discordapp.com/...."`
 - Make sure that the timezone of the PC is correct. If you're running the bot on cloud, you may want to manually change the timezone of the virtual machine to an appropriate time zone (i.e., the timezone that your online classes follow)

## Install
