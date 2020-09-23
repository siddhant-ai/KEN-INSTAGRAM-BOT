#Installation Setup For Developers.                                                                                          
----------------------------------------------------------------------------------------------------------------------------------------------                                                                                                                            |
(1) Downloads all files from My Github Account (https://www.github.com/siddhant-ai)                                                           |
(2) Extract all the RAR files 📂 to you favourite folder.                                                                                     |
(3) Use Supported Py editor (Visual Studio code or PyCharm) If you don't have then dowwnload it from official website.                        |
(4) Open Folder where you extracted it from RAR then Open it in Visual Studio Code/Pycharm (Open Visual SCc Click on File                     |
in header section top left corner, Click on Open folder 📂 and select ectracted Code folder)                                                  |
----------------------------------------------------------------------------------------------------------------------------------------------|
#Editing Python Files given in the folder (setup.py)                                                                                         |
----------------------------------------------------------------------------------------------------------------------------------------------|
(1) Create another Instagram account for your bot, don't use your Original account as Bot Account.                                            |
(2) Open "setup.py": in VS Code, Edit line 16 {input("your bot account username"} example;{input("ken_to_bot")}                              |
(3) In line 19 "setup.py", edit {username = input("Enter your Origial Instagram Username")} example; {username = input("akshay_kumbhar15")}  |
(4) Download Discord app, make server in Discord, make channel for your bot and name it. In the channel setting go to Integration and make a  |
WebHook in Discord and copy the link of your webhook.                                                                                         |
(5) In line 21 "setup.py" {discord_webhook_url = input("paste your Discord webhook url here")}                                               |
----------------------------------------------------------------------------------------------------------------------------------------------|
#Editing Python Files given in the folder (discord_webhook.py)                                                                                |
----------------------------------------------------------------------------------------------------------------------------------------------|
(1) Open Discord_webhook.py file in Visual Studio Code/Pycharm.                                                                               |
(2) In line 5 "discord_webhook.py", edit {WEBHOOK_URL = 'Paste your Discord webhook url there'}                                               |
----------------------------------------------------------------------------------------------------------------------------------------------|
#Editing Python File (follower_check.py)                                                                                                      |   
----------------------------------------------------------------------------------------------------------------------------------------------|
(1) In line 14 of "follower_check.py", Enter Your Bot Insta ID                                                                                |
(2) In line 17 of "follower_check.py", Enter Password of your created Bot ID.                                                                 |
(3) IN line 20 of "follower_check.py", Enter your original account ID to monitor your Followers.                                              |
(4) In line 25 of "follower_check.py", Enter your copied Webhook Discord Url.                                                                 |
----------------------------------------------------------------------------------------------------------------------------------------------|
#Using Bot for Instagram                                                                                                                      |
----------------------------------------------------------------------------------------------------------------------------------------------|
(1) Open Browser and search for www.pythonanywhere.com                                                                                        |
(2) Create your account and then log in into it.                                                                                              |
(3) In Main Dashboard you will find category named "Files" then open that category.                                                           |
(4) In "Files" you will see Upload Files in Yellow button, click on that.                                                                     |
(5) Select edited bot folder and upload all file one by one including requirements.txt too.                                                   |
(6) After uploading You will see "Open Bash Controller here" click on that and open Bash Controller.                                          |
(7) After opening type this commant ("python3 setup.py") and do the setup with correct information as you entered in files                    |
(8) After Setup, type this command ("python3 follower_check.py") and then this file will analyse your instagram and will send                 |
    this information to your Discord server through your Bot.                                                                                 |
(9) Now you can Exit the Bash controller and turn off your computer.Save all edited information                                               |
(10) This Bot will notify you after every half hour whenever someone unfollows you.                                                           |
--------------------------------------------------------------------------------------------------------------------------------------------- |
$# You all done with this setup. Hope you will like this. Please support by following me on GitHub and Instagram.
https://www.github.com/siddhant-ai            (GitHub)
https://www.instagram.com/gadekar_siddhant15  (Instagram)