<h1 align="center">GADS 2020 community project</h1>
<p align="center">
    <img src="https://by3302files.storage.live.com/y4mi90GecD9NnUlaYMWBx8DD2B6HlwtM3Jlrj_FmsSN9I2MXlIMWvGjKZauh-1_Aseyn5CUxjAyNQVXbMXHvzopVBHFrqf7XP-Ix47pq-szoJ2hh6Dl-Pj8CnrFqrcCJpsWd0rhyREuWjPj53Z6WDTfo2ThUOpMVKXAc03FwpNK5Csb-SO1X7a8G0NbecxDiJ2Wq06crj2xklLV7Q-AftH0Lg/122754_18523474_3378663_d1c15cf7_image%20%282%29.png?psid=1&width=564&height=565" width="400">
</p>

<p align="center">
  This project entails a student mentorship android application for the GADS community project. <br/>
  Students enroll as mentors by taking a test to ensure they are well conversant with disciplines they want to mentor others in. <br/>
  Depending on the points they score in the test (if they pass the set passmark), the mentors earn initial reputation points that qualify them to start mentoring others.<br/>
  <br/>
  Students who need help in different disciplines can then enroll as mentees.<br/>
  Upon choosing a discipline, they'll be presented with a list of available mentors in that field, their reputation, comments from other mentees and their hourly rates.<br/>
  Once they settle on a mentor of their liking, they will pay for the number of hours they want to schedule that will only be billed when in active sessions with the mentor. <br/>
  <br/>
  In case the mentee wan'ts a refund, they'll get the unconsumed balance and if a mentee is not satisfied with the services of the mentor, they can vote them down and once a reputation reaches a defined threshold the mentor will be suspended for a defined time. Once the suspension period is over, they will have to retake a test to start mentoring again.
</p>

<p align="center">
  <br/>
  <a href="">
    <img src="https://www.melileashop.sg/assets/img/Google-PlayStore.png" width="240">
  </a>
</p>



## Features / User Stories

A few of the things you can do:

1. As a wannable mentor or mentee on the app I want the ability to login with Google so that I can access the application. <br/>
**End user goal:** Login to the application. <br/>
**Criteria:** * Click continue with Google * Choose a Google Account to use * Get logged in to the application

1. As a wannable mentor or mentee on the app I want the ability to login with my Phonenumber, so that I can access the application. <br/>
**End user goal:** Login to the application. <br/>
**Criteria:** * Click continue with phonenumber * Enter my phonenumber * Receive a OTP code on SMS * Enter the OTP code to the app * Get logged in to the application

1. As a newly registered user I want to be able to set up my profile by filling my full names and selecting my interests, so that I can see a customized feed and be identified by my names. <br/>
**End user goal:** Be identified by name and view customized feed. <br/>
**Criteria:** * Login in for the first time * View a page to enter first name and last name * View a page to select my interests * Save and take me to the dashboard

1. In my dashboard I want to have a profile menu where I can view and edit my details to update my full names and change my interests, so that I can customize my feed. <br/>
**End user goal:** Change my full names and update my interests. <br/>
**Criteria:** * Open my dashboard * Click a profile menu * View my set name and interests * Click an edit button to change my names * Show a dialog to enter new first and last name * Click save and dismiss the dialog * Click on my interests * Launch a dialog with my selected interests followed by other interests * Touch to remove or add my selected interests

1. In my profile page, I want to have see my available balance in cash and minutes, so I plan my schedule and make top-up plans. <br/>
**End user goal:** View my balance. <br/>
**Criteria:** * Open my dashboard * Click a profile menu * Below the personal details above (name and interests) view my balance card * Display my balance in cash and in minutes

1. In my profile page, I want ability to top up my balance or withdraw available balance so I continue pay for sessions. <br/>
**End user goal:** Deposit and withdraw funds. <br/>
**Criteria:** * Open my dashboard * Click a profile menu * In the above balance card, at the bottom show me two buttons (deposit and withdraw) * Onclick the deposit button, show a dialog to enter an Mpesa number and amount * Click a deposit button in the dialog and an STK push will be sent to the phone to complete the payment * After successful payment, update my balance * To withdraw cash * Click on withdraw button * Sheesh (we need to verify user identity to mitigate fraud => **Kindly Help here**)

1. In my profile page, I want to have see my transaction, so I see how I spend my money and time in the app. <br/>
**End user goal:** View my transactions. <br/>
**Criteria:** * Open my dashboard * Click a profile menu * Below the my balance card * Display a list of my transactions (deposits and charges deducted from sessions) sorted by time

1. In my dashboard I want a feed menu to see a list of announcements made by mentor's within my interests (as well as from app maintainers) to be aware of popular topics I might want to learn about. <br/>
**End user goal:** View my customized feed. <br/>
**Criteria:** * Open my dashboard * Click a feed menu (selected by default)* View a list of announcements and posts

1. In my dashboard I want a sessions menu to see a list my past sessions that I can refer to for recap and to learn further. <br/>
**End user goal:** View my historical mentorship sessions. <br/>
**Criteria:** * Open my dashboard * Click a sessions menu * View a list of historical sessions * Click a session, view a transcript of the session * Show the time and money spent on the session

1. In my sessions menu, I want ability to initiate a new session with active mentors in my disciplines of interests so I can get mentorship in a certain field. <br/>
**End user goal:** Initiate a mentorship session. <br/>
**Criteria:** * Open my dashboard * Click a sessions menu * At the top find a button **Open New Session** * Click a the button * Show a dialog to choose one of my disciplines of interest * If none tell me I have none and prompt me to set interests * On Clicking a discipline, show the mentors available at the moment to hold sessions (online or offline) * If th mentor id offline, prompt an error * If the mentor is online open a new session with ability to exchange text and media * Show a counter of time/money spent * Disconnect session incase money is depleted

1. I the dashboard I want a mentor menu to be able to enroll/cancel to becoming a mentor <br/>
**End user goal:** Enroll or cancel to become a mentor. <br/>
**Criteria:** * Open my dashboard and click mentor tab/menu * Show a button to enroll for mentorship * Click on it and launch a dialog * Choose a discipline or add a new one * Show a message you have been enrolled as a mentor * Closing the dialog shows a card, you have been enrolled a mentor and prompts you to take a test 

1. In the mentor tab I want to be able test so I can start mentoring (and earning) <br/>
**End user goal:** Take a test and accumulate initial reputation points to start tutoring. <br/>
**Criteria:** * In the take a test card, click a button **Take Test* * Answer a couple of questions * Get an average score with passed/failed status and reputation points if passed

1. In the mentor tab I want to be able to set my rates and get paid byt eh minute depending on that so I can make money for my mentorship sessions <br/>
**End user goal:** Set rates for mentorship sessions. <br/>
**Criteria:** * After passing the test get a card **Hourly Rates** * Prompt me to set a rate * Get a notification that you are now set to start tutoring

1. In the mentor tab I want to be able to post announcements so I can reach out to potential mentees <br/>
**End user goal:** Post Announcements. <br/>
**Criteria:** * Show a button post announcement * Choose length to display the announcement * Add message and poster * Click Post 



## UI Mock-ups

Here is what to expect:

* Splash screen

<p align="center">
  <img src ="https://colorlib.com/wp/wp-content/uploads/sites/2/21_android-mockup.jpg" width=700>
</p>
