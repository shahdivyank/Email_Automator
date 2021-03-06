# Email-Automator

Made for California Robotics Academy to automate the registration email process. 

An email automator that automatically sends registration confirmation emails when run. The script will read Google Forms data through a Google Drive/Sheets API and send an email if necessary. The email will provide personalized information, addressing the reciever by their name, and confirming the program they signed up and providing any necessary information to ensure they are able to attend classes. 

A template email draft is saved inside of message.txt. Any values to be changed are noted by an opening and closing "__". The script will extract these placeholders and replace them with the appropriate data. The data may be constant or variable. If constant, the user is asked to enter the value for the placeholder. Otherwise, if variable, the script will search through the spreadsheet for a matching name column and retrieve that data instead. Once the data is entered, the script will login to Gmail and send the emails. The amount of emails sent will vary based on Internet providers as many have a limit (100 for most personal use). 

An image of the spreadsheet used is provided below with the user data removed for user security and privacy.

![Sample Spreadsheet Data](https://github.com/shahdivyank/Email_Automator/blob/main/images/sample_data.png)

An image of the resulting email is provided below with all the custom information. Sample Data has been used to protect user security and privacy.

![Sample Emails](https://github.com/shahdivyank/Email_Automator/blob/main/images/sample_email.png)

<p align= "center">Feel free to connect with me on any of the following platforms to talk about question, possible collaborations, opportunities, events, tech, or for fun!! Can't wait to meet you!</p>
<p align = "center">
  <a href="https://www.linkedin.com/in/divyank-shah/" target = "_blank">
    <img src="https://evergreenengineering.com/wp-content/uploads/2019/06/LinkedIn_logo_initials.png" width = 60px>
  </a>

  <a href="https://instagram.com/divyank.shah" target = "_blank">
    <img src="https://i.dlpng.com/static/png/6382269_preview.png" width = 90px>
  </a>

  <a href="https://github.com/shahdivyank" target = "_blank">
    <img src="https://www.tethysplatform.org/images/github-icon.png" width = 65px>
  </a>

  <a href="mailto:divyank.shah.2016@gmail.com" target = "_blank">
    <img src="https://logos-world.net/wp-content/uploads/2020/11/Gmail-Logo.png" width = 100px>
  </a>
</p>
