<img width="348" height="1280" alt="image" src="https://github.com/user-attachments/assets/6d7c26c3-5e32-41cd-b873-66099687be50" /><img width="348" height="1280" alt="image" src="https://github.com/user-attachments/assets/54017c2b-e0f0-4cd8-979c-f289690aa3b1" /><img width="547" height="1280" alt="image" src="https://github.com/user-attachments/assets/b31f9ed5-24e2-4c46-907d-6b2ca9e9863c" /># SmartMirror
My Smart Mirror project

# ABSTRACT 
  A Smart Mirror is a two way mirror, TV based on the idea of smart interaction including touch functionalities. It will be prevalently used to display real time updates and prompt notifications like weather, traffic, calendar, news feeds, maps and social media with an intelligent open-ended voice search interface in the form of widget. It will be a gadget based interface to urge information with different administrations. Many open source API's like Google maps API, Google Cal and open weather chart API were used for gathering information from the internet.

  This product would be useful for busy individuals that want to multitask and stay informed while ont he go. Instead of contantly pulling out a device, one could get informed while finishing daily grooming tasks. Multipurpose mirror that is meant to serve as both decoration and good time management and for security purposes also.
  One such thing is that the Internet of Things(IoT), which is a brefing of interrealted devices with the capacity to send information over a system without expecting H2H(Human 2 Human) or H2M (Human 2 Machine) collaboration

  TABLE OF CONENTS
  CHAPTER 1: INTRODUCTION 
  1.1 Background 
  1.2 Objectives
  1.3 Purpose, Scope, and Apllicability
    1.3.1 Purpose 
    1.3.2 Scope
    1.3.3 Applicability
  CHAPTER 2: SURVEY OF TECHNOLOGIES
  CHAPTER 3: REQUIREMENTS AND ANALYSIS
  3.1 Problem Defination
  3.2 Software Requirements Specification
  3.3 Planning and Scheduling 
  3.4 Software and Hardware Requirements
  3.5 Conceptual Models
  CHAPTER 4: SYSTEM DESIGN
  4.1 Basic Modules
  4.2 Data Design
    4.2.1 Schema Design
    4.2.2 Data Integrity and Constraints 
  4.3 System Design
  CHAPTER 5: IMPLEMENTATION AND TESTING 
  5.1 Installation and Usage 
  5.2 Manual Installation and Alternative Installation
  CHAPTER 6: CONFIGURATION
  6.1 Introduction
  6.2 Config the pi
  6.3 Configure sound
  6.4 Configure the smart-mirror
  6.5 Autostart Magic mirror
  CHAPTER 7: MODULES
  7.1 Model configuration
    7.1.1 alert
    7.1.2 calendar
    7.1.3 clock
    7.1.4 compliments
    7.1.5 news feed
    7.1.6 update notification
    7.1.7 weather module
  CHAPTER 8: REFERENCE 

  *******************************************************

CHAPTER 1. INTRODUCTION
  In this world everyone needs a comfortable life. Modern man has invented different technology for his purpose. In today's world, people need to be connected and they are willing to access the information easily. Whether it is through the television or internet, people need to be informed and in touch with the current affairs happening around the world.
   The Internet of Things means interconnection via the internet of computing devices embedded in everyday objects, enabling them to send and receive data.
The IoT with its enormous growth widens its applications to the living environment of the people by changing a home to a smart home. Smart home is a connected home that connects all types of digit devices to communicate with each other through tne internet. Our lifestyle has evolved in such a way that optimizing time is the most important thing. Our work is based on the idea that we all look at the mirror when we go out, so why wouldn't the mirror became smart. A common approach for building a smart mirror is to use a high quality two way mirror, Display, a frame to hold the glass and Display and a web browser with python to provide the software features and drive the display.

1.1 BACKGROUND 
  Now a days, World has been inrofuced to the new terms called Technology. Technology makes out world smart that such things we are creating for a perfect life and to make our daily life easier.
  Smart things like mobile phones, computers, smart furniture,etc. we are now using, like those things we can use our home's normal mirror as smart mirror, this mirror can help us to be updated.
        Time is what we want most, but, what we use worst - William Penn
  The requirement of this device would be a discovery where the technology and therefore the ordinary elements of human life to merge and supply a far better experience. Generally the smart mirrors are used to know the time, whether outlook, social media greetings, and claendar based notifications.

1.2 OBJECTIVES
  Recent advancements in technology have paved the way to automate things around us. Smart phones, tablets, Personal Computers provide us up-to-date information with respect to current news, social media, and personal appointments but still they all are a means of distraction as they interrupt one's routine. They cannot be carried everywhere as there is a risk of damage.
  Our solution to the problem is to turn the mirror smart.
  The product provides updates about news, weathers and Features of the system should fulfill the purpose of the system. There are many categories of user, the User can be a busy person or a businessman, so it is little difficult to be a user to maintain and make daily routines or schedule meetings times and date, The major focus should be on the customer needs and their problems with respect to the smart mirror.
  We kow developing this product is not easy because contains many programs and funtions. The product is developed to work efficiently and effectively. It can be observed that the information can be obtained easily and accurately.

1.3 PURPOSE, SCOPE AND APPLICABILITY

1.3.1 PURPOSE
  Smart Mirrors feature a digit display behind the glass and connect to your phone via blutooth or Wifi. Through this display, you can typically get:
    1. Latest news
    2. Latest weather forecast, date and time
    3. Entertainment
    4. Home Security
    5. Real time interaction with users

1.3.2 SCOPE
  1. No need to contantly pulling out a device for updates
  2. Get news, weather related updates on the display
  3. The hidden camera is used to monitor unusual behavior in your room
  4. Connected with your local devices for immediate updates
  5. Voice assistant
  6. Must be connected to the web to receive incoming data

1.3.3 Applicability 
  1. Touch screen
  2. LED lighting
  3. Motion sensor
  4. Voice control
  5. Adjustable images switching times
  6. Auto detection of firewall

CHAPTER 2: SURVEY OF TECHNOLOGIES

  The primary hardware component for our system is the Raspberry Pi. In particular, we use the Raspberry Pi 3 as it maintains the same price point but offers additional processing power, more RAM, and offers onboard bluetooth and WiFi for connectivity. The Raspberry Pi was selected for its ease of use and availibility to the hobbyist community. The Rasberry Pi is capable of running several flavors of Linux, all of which should be capable of running our software platform.
  The Smart Mirror concept is like something amazing is going to happen. Before going to complete it, we have to decide what we are going to do and how it will be done. After the Raspberry pi connection we have to write some programs for display. As we know raspberry pi works in linux based system and better know python languages, so we are going to use HTML and CSS as a front-end language, JavaScript to implement the entirely of the system. Python & .NET as a backend language.
  In order to host the source code and other components of the project, a version control system was neccessary. GitHub was chosen for its familiarity and compatibility with other technologies. GitHub allowed for multiple developers to work on the project at once and keep track of version history. Other users can access the project from GitHub and obtain any version of the project.
  Because of GitHub's compatibility with other software, we chose to use Travis CI to run tests on out system. On any change in the GitHub repository, Travis CI runs all tests we have written and reports the results. This helps track changes in the system's functionality and catch bugs as they are introduced.
  
CHAPTER 3: REQUIREMENTS AND ANALYSIS 
3.1 Problem Definition
  A smart mirror is a device that functions as a mirror with additional capability of displaying multimedia data, such as text, images and videos. This device allows users to access and interact with contextual information, such as weather data, seamlessly as part of their daily routine.
  The world we live in today has become a place of the fiercest competition, whether it is in sports, entertainment, or the job market. In order to be the best, one needs to allocate an extraordinary amount of time to their goals with little distraction. However, the advent of information technology tends to act like a dual-edged sword when it comes to work productivity; sometimes one can use the ease of information to help them complete a task, but it can also provide significant distraction. Ultimately one strives to be their best, but the interruption of keeping up with the daily news, or preparing for incoming weather can hinder one's progress. Taking timethrouhgout the day for these various activities can be extremely distracting and greatly cut into performance.
  Along with information, people greatly value their appearance, spending approximately an hour a day in front of the mirror during their morning and night routines. This is a significant amount of time where important things are taking place, but the mind is not working. It would be extremely useful to spend that time on the phone or computer completing any of the tasks mentioned above, but unfortunately it is difficult to do so while preparing for the day. A product is needed that can allow a person to efficiently complete everything they need to do to prepare for the day, all in one place and at all the same time.

3.2 SOFTWARE REQUIREMENTS SPECIFICATION
  The software tools that were to be used for developing the samrt mirror are:
    1. Raspbian Operating System
    2. Pythonscript - Which is to be used to develop the IR-sensor with the Raspberry PI processor and IR-sensor led.

Months	June			July				Aug				Sep					Oct				Nov					Dec				Jan				Feb				March				Apr
Weeks	w3	w4	w5	w1	w2	w3	w4	w1	w2	w3	w4	w1	w2	w3	w4	w5	w1	w2	w3	w4	w1	w2	w3	w4	w5	w1	w2	w3	w4	w1	w2	w3	w4	w1	w2	w3	w4	w1	w2	w3	w4	w1
Introduction																																										
Background																																										
Objectives																																										
Purpose																																										
Scope																																										
Applicability																																										
Survey of technology																																										
Requirements and Analysis																																										
Problem definition																																										
Software requirements specification																																										
Planning and scheduling																																										
Software and Hardware Requirements																																										
Concepts Models																																										
System Design																																										
Basic Modules																																										
Data design																																										
Schema design																																										
Data Integrity and constrains																																										
System Design																																										
Implementation and Testing																																										
Installation  and Usage																																										
Manual Installation and Alternative Installation																																										
Configuration																																										
introduction																																										
Config the Pi																																										
Configure sound																																										
Configure the smart mirror																																										
Autostart Magic Mirror																																										
Modules																																										
Introduction																																										
Model Configuration																																										
Alert																																										
Calender																																										
Clock																																										
Compliments																																										
News feed																																										
Update notification																																										
Weather module																																										
Preferences																																										

3.4 SOFTWARE AND HARDWARE REQUIREMENTS
Hardware Requirements:
  1.Raspberry pi model 3 A/B/B+
  2. HDMI cable
  3. Raspberry pi camera
  4. Ultrasonic sensor
  5. Sound sensor
  6. LCD display
  7. Two way mirror
  8. Speakers
  9. Amplifier
  10. Jumper Wires

Software Requirements:
  The software tools that were to be used for developing the samrt mirror are:
  1. Raspbian Operating System
  2. Pythonscript - which is to be used to develop the IR-senosor with the Raspberry PI processor and IR-sensor led.

3.5 Conceptual Models (Spiral Model)

<img width="600" height="500" alt="Spiral_model_(Boehm,_1988)" src="https://github.com/user-attachments/assets/f8180031-3bb5-409e-ba98-ed3d97a9cda6" />

INCREMENTAL LIFE CYCLE MODEL

<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/ca2ab440-15d3-4122-86d4-1e99f22ee234" />

CHAPTER 4: SYSTEM DESIGN
4.1 BASIC MODULES
USE CASE DIAGRAM

<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/492b27ef-39a2-44c4-a779-f3ac54b4e910" />

4.2 DATA DESING
4.2.1 SCHEMA DESIGN

<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/835101c1-5cf1-45bf-959f-7d41754dee50" />

4.2.2 DATA INTEGRITY AND CONSTRAINTS

<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/0ec9d6bd-625f-4a73-bc76-44564ad7af2a" />

4.3 SYSTEM DESIGN

ACTIVITY DIAGRAM

<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/e5787a07-2925-4094-8f4a-38f2f973d8f0" />

FLOW CHART

<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/e9135e0a-577b-4f3e-9b41-09080991414b" />

CHAPTER 5: IMPLEMENTATION AND TESTING 
5.1 INSTALLATION AND USAGE
  The Magic Mirror can be installed manually or using automatic installers. At the start of 2020 the decision was made to remove the automatic installer from the Smart Mirror core respository and move it to a community maintained separate repository. For more information about this decision, please check issue #1860 on GitHub.
  Therefore the only officially supported way of installation is by using a manual installaion. Using external installation scripts is at your own risk but can make the process a lot easier. Available automatic installers can be found under: alternative installation methods

5.2 MANUAL INSTALLATION AND ALTERNATIVE INSTALLATION
ALTERNATIVE INSTALLATION METHODS:
  The following installation methods are not maintained by the Smart Mirror core team. Use these scripts and methods at your own risk.

Automatic Installation Scripts
  Sam (@sdetweil, long time contributor of the Smart Mirror framework) maintains a easy to use installation and update script: https://github.com/sdetweil/SmartMirror_scripts

  The Smart Mirror Package Manager is a command line interface designed to simplify the installation, removal, and maintenance of Smart Mirror modules.

Docker Image
  Smart Mirror can be deployed using Docker. Head over to this repository for more information.

Kubernetes Helm Chart
  If you want to run Smart Mirror (in server only mode) in a kubernetes cluster then take a look at this Smart Mirror Helm Chart.

Smart MirrorOS
  This is a full OS based on Raspbian. So instead of downloading Raspbian and putting this on you sd card, you can use Smart MirrorOS instead. It runs out of the box with a default setup of Smart Mirror, under the hood it used the docker setup

CHAPTER 6: CONFIGURATION
6.1 INTRODUCTION
  1. Copy/home/pi/Smart Mirror/config/config.js.sample to /home/pi/Smart Mirror/config.js.
     NOTE: If you used a third-party installer script, this step may already have been done for you.
  2. Modify your required settings.
     NOTE: You can check your configuration running npm run config:check in/home/pi/Smart Mirror.

The following properties can be configured:
Option 
  port
    Description - The port on which the Smart Mirror server will run on. The default value is 8080.
  address
    Description - The interface ip address on which to accept connections. The default is localhost, which would prevent exposing the built-in webserver to                          machines on the local network. To expose it to other machines, use: 0.0.0.0.
  ipWhitelist
    Description - The list of IPs from which you are allowed to access the Smart Mirror. The default value is ["127.0.0.1","::ffff:127.0.0.1"], which is from                        localhost only. Add your IP when needed. You can also specify If ranges with subnet masks(["127.0.0.1","127.0.0.1/24"]) or directly with                           (["127.0.0.1",["192.168.0.1","192.168.0.100"]]). Set[] to allow all IP addresses. For more information see: follow post ipwhitelist How to
  language 
    Description - The language of the interface. (Note: Not all elements will be localized.) Possible values are en, nl, ru, fr, etc., but the default value is en.
  timeFormat
    Description - The form of time notation that will be used in the default weather modules. Possible values are 12 or 24. The default is 24.
  units
    Description - The units that will be used in the default weather modules. Possible values are metric or imperial. The default is metric.
  modules 
    Description - An array of active modules. The array must contain objects. See module configuration for more information.
  customCss
    Description - The path of the custom.css stylesheet. The default is css/custom.css.

6.2 CONFIG THE PI
   Edit the /home/pi/.config/lxsession/LXDE-pi/autostart file with nano/home/pi/.config/lxsession/LXDE-pi/autostart.

   Recommended to disable the screensaver you'll wnat to comment out (with a'#') the @xscreensaver. You'll also want to add the following lines to that same file 
   @xset s off
   @xset -dpms
   @xset s noblank

  Optional to remove the panel at the top of the screen to comment out the @lxpanel lines. If you want  to be able to easily access the "menu" at the top of the screen do not do this step.
  Hide the mouse when inactive
  sudo apt-get install unclutter

  Then Add unclutter -idle 0.1 -root to /etc/xdg/lxsession/LXD-pi/autostart with sudo nano /etc/xdg/lxsession/LXDE-pi/autostart

6.3 CONFIGURE SOUND
  Audio Output
  Should you want to change the output from AUX (headphone jack:
      amixer cset numid=3 1
  To force the audio back through HDMI you can run:
      amixer cset numid=3 2

6.4 CONFIGURE THE SMART-MIRROR
  The smart-mirror is configured using the Remote Configuration tool. This requires you to start the mirror.
    Open th terminal and type:
      npm start
      or
      pm2 start smart-mirror ( if you selected yes to pm2 to manage starting during isntall)
  There are 2 ways to find the IP and port of the remote for the mirror:
    From the command line 
    When the mirror starts it will output the remote IP and port to the command line: 
      >smart-mirror@0.0.27 start /Users/evan/Git/smart-mirror
      >electron main.js
    Remote listening on http://192.168.1.130:8080
    From a QR code
  If you're running the mirror for the first time (or for the first time since running upgrading to this version of the mirror) you'll see a QR Code with a URL      under it. From a phone or another computer (on the same network as your Smart-Mirror) you can open a browser and manually enter the URL.
  If you're not running the mirror for the first time and you've properly configured the Sound and Voicek, say the keyword/hotword and the "Show Remote Link" to     display the URL to reach the Remote Configuration Tool.
  Update Settings
  After going to the Homepage of the remote, click on settings>configure the Mirror.
  It is required that you fill out Speech Settings!
  URL under it. From a phone or another computer (on the same network as your Smart-Mirror) you can open a browser and manually enter the URL.
  If you're not running the mirror for the first time and you've properly configured the Sound and Voice, say the keyword/hotword and then "Show Remote Link" to display the URL to reach the Remote Configuration Tool.
  Update Settings
  After going to the Homepage of the remote, click on Settings>Configure the Mirror
  It is required that you fill out Speech Settings!

CHAPTER 7: MODULES
7.1 MODULES CONFIGURATION
  The module configuration is used as part of the main configuration file. Please see configuration for more information.

  Options :
    module 
      Description - The name of the module. This can also contain the subfolder. Valid examples include clock, default/calendar and custom modules/mymodule.
    position
      Description - The location of the module is which the module will be loaded. Possible values are top_bar, top_left, top_center, top_right, upper_third,                          middle_center, lower_third, bottom_left, bottom_center, bottom_right, bottom_bar, fullscreen_above, and fullscreen_below. This field is                            optional but most modules require this field to set. Check the documentation of the module for more information. Multiple modules with the                         same position will be ordered based on the order in the cofiguration file.
    classes
      Description - A list of additional CSS classes which will be set on the module. This field is optional.
    header
      Description - To display a header text above the module, add the header property. This field is optional.
    hiddenOnStartup
      Description - Set module as being hidden on startup. This field is optional.
    disabled 
      Description - Set disabled to true to skip creating the module. This field is optional.
    config 
      Description - An object with the module configuration properties. Check the documentation of the module for more information. This field is optional, unless                     the module requries extra configuration.
#
  Example 

    let = {
            : [ 
    { 
            : "clock",
              : "top_left",
    },
    {
            : "compliments",
              : "lower_third",
    },
    {
            : "weather",
              : "top_right",
            : {
                  : "openweathermap",
            : "current", 
              : "New York",
                : "5128581", //ID from http://bulk.openweathermap.org/sample/city.list.json.gz; unzip the gz file and find you city
              : "YOUR_OPENWEATHER_API_KEY",
      
              },
            },
          ],
      };

Position
  The locations can be found inthe following screenshot by their color:
    1. top_bar and bottom_bar are light gray
    2. top_left and bottom_left are red
    3. top_center and bottom_center are blue
    4. upper_third is yellow
    5. middle_center is cyan
    6. lower_third is magenta
    <img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/c0aae5cb-2836-4467-ae5a-1f2db7541fff" />
7.1.1 ALERT
  The alert module is one of the default modules of the Smart Mirror. This module displays notifications from other modules.
  Usage
    To use this module, add it to the modules array in the config/config.js file:
      { 
          module: "alert",
          config: {
                    // The config property is optional.
                    // See 'Configuration options' for more information.
                  }
        }

  CONFIGURATION OPTIONS
    The following properties can be configured:
    Options 
    effect 
      Description - The animation effect to use for notifications.
                    Possible values: scales slide genie jelly flip exploader bouncyflip
                    Default value: slide
    alert_effect 
      Description - The animation effect to use for alerts.
                    Possible values: scale slide genie jelly flip exploader bouncyflip 
                    Default value: jelly
    display_time 
      Description - Time a notification is diplayed in milliseconds.
                    Possible values: int
                    Default value: 3500
    position
      Description - Position where the notification is diplayed in milliseconds.
                    Possition values: left center right
                    Default values: center
    welcome_message
      Description - Message shown at startup.
                    Possible values: string false
                    Default value: false (no message at startup)

DEVELOPER NOTES
  for notification use:
  for alerts use:

  Options :
    title 
      Description - The title of the notification.
                    Possible values: text or html
    message 
      Description - The message of the notification.
                    Possible vlaues: text or html
    timer(optional)
      Description - How long notification should stay visible in ms.
                    If absent, the default display_time is used.
                    Possible values: int float

ALERT PARAMS
  Options
    title 
      Description - The title of the alert.
                    Possible values: text or html
    message
      Description - The message of the alert.
                    Possible values: text or html
    imageUrl (optional)
      Description - Image to show in the alert
                    Possible values: url path
                    Default value: none
    imageFA (optional)
      Description - Font Awesome icon to show in the alert
                    Possible values: See Font Awesome website.
                    Default value: none
    imageHeight (optional even with imageUrl set)
      Description - Height of the image
                    Possible values: intpx
                    Default value: 80px
    timer (optional)
      Description - How long the alert should stay visible in ms.
                    Important: if you do not use the timer, it is your duty to hide the alert by using 
                    self.sendNotification("HIDE_ALERT");!
                    Possible values: int float
                    Default value: none
    title 
      Description - The title of the alert.
                    Possible values: text or html
    message 
      Description - The message of the alert
                    Possible values: text or html
    imageUrl(optional)
      Description - Image to show in the alert
                    Possible values: url path
                    Default value: none
    imageFA(optional)
      Description - Font Awesome icon to show in the alert
                    Possible values: See Font Awesome website.
                    Default value: none
    imageHeight(optional even with imageUrl set)
      Description - Height of the image
                    Possible values: intpx
                    Default value: 80px
    timer (optiona)
      Description - How long the alert should say visible in ms.
                    Important: if you do not use the timer, it is your duty to hide the alert by using 
                    self.sendNotification("HTDE_ALERT");!
                    Possible values: int float
                    Default value: none

7.1.2 CALENDAR
  To use this moudle, add it to the modules array in the config/config.js file:
    {
  {
        : "calendar",
          :{
            // The config property is optional.
            // If no config is set, an example calendar is shown.
            // See 'Configuration options' for more information.
          },
        }
    };

CONFIGURATION OPTIONS
  The following properties can be configured:
  Option 
    maximumEntries 
      Description - The maximum number of events shown. /Possible values: 0 = 100
                    Default value: 10
    maximumNumberOfDays 
      Description - The maximum number of days in the future.
                    Default value:365
    pastDaysCount
      Description - The nubmer of days of which events in the past should be displayed.
                    Default value = 0
    displaySymbol
      Description - Display a symbol in front of an entry.
                    Possible values: true or false
                    Default value: true
    defaultSymbol 
      Description - The default symbol.
                    Possible values: See Font Awesome website.
                    Default value: calendar
    showLocation
      Description -   Whether to show event locations.
                      Possible values: true or false
                      Default value: false
    maxTitleLength
      Description - The maximum title length.
                    Possible values: 10-50
                    Default value: 25
    maxLocationTitleLength
      Description - The maximum location title length.
                    Possible values: 10-50
                    Default value: 25
    dataEndFormat
      Description - Format to use the end time of events
                    Possible values: See Moment.js formats
                    Default value: HH:mm(e.g. 16:30)
    coloredSymbolOnly(deprecated)
      Description - If this property is set to true, an individual symbol color can be set for each clendar, not the whole line. This is only applicable when                          colored is also enabled.
                    Default value: false
    colorText
      Description - If this property is set to true, an individual text color can be set for each calendar.
                    Default value: false
    coloredBorder
      Description - If this property is set to true, an individual border color can be set for each calendar.
                    Default value: false
    coloredSymbol
      Description - If this property is set to true, an individual symbol color can be set for each calendar.
                    Default value: false
    coloredBackground
      Description - If this property is set to true, an individual background color can be set for each for calendar.
                    Default value: false

    Default value: 
          : {
                  : false,
                    : false,
                    : false,
                      :false ,
                        :[
                  { 
          'https://www.calendarlabs.com/templates/ical/US-Holidays.ics'
                  : 'calendar',
                    :{
                        : 'username',
                        : 'superstrongpassword',
                          : 'basic'
                    }
                },
            },
          ],
        }

7.1.3 CLOCK
  The clock module is one of the default modules of the Smart Mirror. This module displays the current date and time. The information will be updated realtime.
    1. Current time
    <img width="547" height="1280" alt="image" src="https://github.com/user-attachments/assets/0d0d99a4-1c44-4456-bc6a-c3c011b5abb3" />
USING THIS MODULE
  To use this module, add it to the modules array in the config/config.js file:
    :[
{
        : "clock",
            : "top_left", //This can be any of the regions.
            :{ 
            //The config property is optional.
            // See 'Configuration options' for more information.
            },
            },
          ];

CONFIGURATION OPTIONS
  The following properties can be configured:
    Option
      timeFormat
        Description - Use 12 or 24 format.
                      Possible values: 12 or 24
                      Default value: uses value of config.timeFormat
      timezone
        Description - Specific a timezone to show clock.
                      Possible examples values: America/New_York,America/Santiago,Etc/GMT+10
                      Default value: none. See more information about configuration value here 
      displaySeconds
        Description - Display seconds.
                      Possible values: true or false
                      Default value: true
      showPeriod
        Description - Show the period (am/pm) with 12 hour format.
                      Possible values: true or false
                      Default value: true
      showPeriodUpper
        Description - Show the period (AM/PM) with 12 hour format as uppercase.
                      Possible values: true or false
                      Default value: false
      clockBold
        Description - Remove the colon and bold the minutes to make a more modern look.
                      Possible values: true or false
                      Default value: false
      showTime
        Description - Turn off or on the Time section.
                      Possible values: true or false
                      Default value: true
      showDate
        Description - Turn off or on the date section.
                      Possible values: true or false
                      Default value: true
      showWeek
        Description - Turn off or on the Week section.
                      Possible values: true or false
                      Default value: false
      showSunTimes
        Description - Turn off or on the section showing sunrise and sunset times (digital clock only).
                      Possible valeus: true or false
                      Default value: false
      showMoonTimes
        Description - Turn off or on the section showing moonrise and moonset times (digital clock only).
                      Possible values: true or false
                      Default value:false
      lat 
        Description - Latitude for sun/moon calculations.
                      Default value: 47.630539
      lon 
        Description - Longitude for sun/moon calculations.
                      Default value: -122.344147
      dateFormat
        Description - Configurethe date format as you like.
                      Possible values: Docs
                      Default value: "dddd, LL"
      displayType
        Description - Display a digital clock, analog clock, or both together.
                      Possible values: digital, analog, or both
                      Default value: digital
      analogSize
        Description - Specificto to the analog clock. Define how large the analog display is.
                      Possible values: A positive number of pixels 
                      Default value: 200px
      analogFace
        Description - Specific to the analog clock. Specifies which clock face to use.
                      Possible values: simple for a simple border, none for no face or border, or face-###(where ### is currently a value between 001 and 012,                           inclusive)
                      Default value: simple
      secondsColor
        Description - Specific to the analog clock. Specifies what color to make the 'seconds' hand.
                      Possible values: any HTML RGB Color
                      Default value: # 888888
      analogPlacement
        Description - Specific to the analog clock. (requires displayType set to 'both') Specifies where the analog clock is in relation to the digital clock
                      Possible values: top, right, bottom, or left
                      Default value: bottom
      analogShowData
        Description - Obsolete, can be replaced with analogPlacement and showTime.
                      Specific to the analog clock. If the clock is used as a separate module and set to analog only, this configures whether a date is also                             displayed with teh clock.
                      Possible values: false, top, or bottom
                      Default value: top
      sendNotifications
        Description - Enable notifications for elapsed time. Used to be always done send prio to v2.23
                      Possible values: true, or false
                      Default value: false
NOTIFICATIONS
  The clock makes use fo the built-in Notification Mechanism to relay notifications to all modules.
  Current notifications are:
    Notifications 
      CLOCK_SECOND
        Description - A second has elapsed.
                      Parameter: second value
      CLOCK_MINUTE
        Description - A minute has elapsed 
                      Parameter: minute value

7.4.4 COMPLIMENTS
  The compliments module is one of the default modules of the Smart Mirror. This module displays a random compliment.
  Screenshots
    1. compliments Screenshot
        <img width="348" height="1280" alt="image" src="https://github.com/user-attachments/assets/2a2aebf0-cfb7-4f4b-a82a-cb3d8cc807b7" />
# 
  Using the module
    To use this module, add it to the modules array in the config/config.js file:
      : [
    {
        : "compliments",
          : "lower_third", // This can be any of the regions.
          // Best results in one of the middle regions like lower_third
            : {
            // The config property is optional.
            // If no config is set, the default complimetns are shown.
            // See 'Configuration options' for more information.
            },
          },
          ];

Configuration options
  The following properties can be configured:
  Option
    updateInterval
      Description - How often does the compliments have to change? (Milliseconds)
                    Possible values: 1000 - 86400000
                    Default value: 30000 ( 30 seconds)
    fadeSpeed
      Description - Speed of the update animation. (Milliseconds)
                    Possible values: 0-5000
                    Default value: 4000 (4 seconds)
    compliments
      Description - The list of complimetns.
                    Possible values: An object with four arrays: morning, afternoon, evening and anytime. See compliment configuration below.
                    Default value: See compliment configuration below.
    remoteFile
      Description - External file from whic to load the compliments
                    Possible values: Path or URL (starting with http://or https://) to a JSON file containing compliments, configuration (see below). An object                        with four arrays: morning, afternoon, evening and anytime. - complimetns.json
                    Default value: thin xlarge bright
    classes
      Description - Override the CSS classes of the div showing the compliments
                    Default value: thin xlarge bright
    morningStartTime 
      Description - Time in hours(in 24 format), after which the mode of "morning" will begin
                    Possible value: 0 - 24
                    Default value : 3
    morningEndTime  
      Description - Time in hours (in 24 format), after which the mode of "morning" will end
                    Possible values: 0- 24
                    Default value: 12
    afternoonStartTime
      Description - Time in hours (in 24 format), after which the mode "afternoon" will begin
                    Possible values: 0-24
                    Default value: 12
    afternoonEndTime
      Description - Time in hours (in 24 format), after which the mode "afternoon" will end
                    Possible values: 0-24
                    Default value: 17

All the rest of the time that does not fall into the morningStartTime-morningEndTime and afternoonStartTime-afternoonEndTime ranges is considered "evening".

#
  COMPLIMENT CONFIGURATION
    The compliments property contains an object with at least four arrays: morning, afternoon, evening and anytime. Based on the time of the day, the complimetns      will be picked out of one of these arrays. The arrays contain one or multiple compliments.
    Complimetns can be set for a specific day in the format YYYY-MM-DD. can be used as a wildcard>
    If set, the weather can be used for complimetns. The available properties are:
      1. day_sunny
      2. day_cloudy
      3. cloudy
      4. cloudy_windly
      5. showers
      6. rain
      7. thunderstorm
      8. snow
      9. fog
      10. night_clear
      11. night_cloudy
      12. night_showers
      13. night_rain
      14. night_thunderstorm
      15. night_snow
      16. night_alt_cloudy_windy
#
  Example use wih date
    : {
           : { 
           "....-01-01": [
                     "Happy new year!"
                ],
                "....-10-31": [
                        "Happy Halloween!"
                        ]
                  }
            }
# 
  EXAMPLE USE WITH WEATHER MODULE
    : {
          :{
                :[ 
                "Today is a sunny day",
                "It's a beautiful day"
                ],
                :[
                  "Snowball battle!"
                  ],
                    :{ 
                      "Don't forget your unbrella"
                    ]
                  }
              }
#
  Dafaut value:
          :{
              :{
                  :[
                  "Hey there sexy!"
                  ],
                      :[
                        "Good morning, handsome!"
                        "Enjoy your day!"
                        "How was your sleep?"
                        ],
                          :[ 
                            "Hello, beauty!",
                            "You look sexy!",
                            "Looking good today!"
                            ],
                              :[
                                  "wow, you look hot!"
                                  "You look nice!"
                                  "Hi, sexy!"
                                ],
                                "....-01-01" :[
                                "Happy new year!"
                                ]
                              }
                            }

#
  Multi-line compliments:
    Use \n to split compliment text into multiple lines, e.g. First line.\n.Second line. Will be shown as :

# 
  External Compliment File
    You may specify an external file that contains the three compliment arrays. This is particularly useful if you have a large number of compliments and do not       wish to crowd you config.js file with a large array of complimenst. Adding the remoteFile variable will override an array you specify in the configuration         file.
    This file must be straight JSON. Note that the array names need quotes around them ("morning","afternoon","evening","snow","rain",etc.).
#
  Example config/config.js of a Compliment File hosted on GitHub
    {
    module: 'compliments',
    position: 'middle_center',
      config: {
        remoteFile:
    'https://gist.githubusercontent.com/user/e28a69665b8839f6e9a7acd6b4acc97d/raw/be1dee8f805a433f6ee0fa3556d1927da14e7799/compliments.json'
    }
    }

(When copying the link from Github, you must use the 'Raw' link)

#
  Example compliments.json file:
    { 
        "anytime": ["Hey ther sexy!"],
        "morning": [
          "Good morning, sunshine!",
          "Who needs coffee when you have your smile?"
          "Go get 'em, Tiger!"
          ],
          "evening": [
            "You made someone smile today, I know it."
            "You are making a difference."
            "The day was better for your efforts."
            ]

7.5.5 news feed
  The newsfeed module is one of the default modules of the Smart Mirror. This module displays news headlines based on an RSS feed. Scrolling through news headlines happens time-based (updateInterval), but can also be controlled by sending news feed specific notifications to the module.

# 
SCREENSHOT
  NEWS FEED SCREENSHOT USING THE NYT
    <img width="1280" height="266" alt="image" src="https://github.com/user-attachments/assets/a4763545-932e-4718-a0ef-f4181704e3e4" />
# 
USING THE MODULE
#
COFIGURATION
  To use this moduel, add i to hte modules array in the config/config.js file:
    :[
  {
      : "newsfeed",
        : "bottom_bar", // This can be any of the regions. Best results in center regions.
            : {
            // The config property is optional.
            // If no config is set, an example calendar is shown.
            // See 'Configuration options' for more information.
              :[
            {
                : "New York Times",
              : "https://www.nytimes.com/services/xml/rss/nyt/HomePage.xml"
              }, 
              { 
                    :"BBC",
                  :
            "https://feeds.bbci.co.uk/news/video_and_audio/news_front_page/rss.xml?edition=uk",
              },
            ],
          },
        },
      ];

#
  Notifications
#
  Interactign with the module
    Smart Mirror's notification mechanism allows to send notificaions to the newsfeed module. The following notifications are supported:
  Notification Identifier
    ARTICLE_NEXT 
      Description - Shows the next news title (hinding the summary or previously fully displayed article)
    ARTICLE_PREVIOUS
      Description - Show the previous news title (hiding the summary or previously fully displayed article)
    ARTICLE_MORE_DETAILS
      Description - When received the first time, shows the corresponding description of the currently displayed news title.
                    The module expects that the module's configuration option showDescription is set to false (default value).
                    When received a second consecutive time, shows the full news article in an IFRAME.
                    This requires that the news page can be embedded in an IFRAME, e.g. doesn't have the HTTP response header X-Frame-Options set to e.g DENY.
                    When received the next consecutive times, reloads the page and scrolls down by scrollLength pixels to paginate through the article.
    ARTICLE_LESS_DETAILS
      Description - Hides the summary or full news article and only displays the news title of the currently viewed news item.
    ARTICLE_TOGGLE_FULL
      Description - Toggles article in fullscreen.
    ARTICLE_INFO_REQUEST
      Description - Causes newsfeed to respond with the notification ARTICLE_INFOR_RESPONSE, the payload of which provides the title, source, date, desc and url                       of the current news title.
      Smart Mirror's notification mechanism can also be used to send notifications from the current module to all other modules. The following notifications are         broadcasted from this module:
        Notification Identifier
          NEWS_FEED
            Description - Broadcast the current list of news items.
          NEWS_FEED_UPDATE
            Description - Broadcasts the list of updates news items.
        Note the payload of the sent notification event is ignored.
#
  Example
    The following example shows how the next article title can be diplayed on the Smart Mirror.
      this.sendNotification("ARTICLE_NEXT");
        newsfeed specific notification emitting modules
          The third party MMM-Gestures module supports above notifications when moving your hand up, down, left or right in front of a gesture sensor attached               to the Smart Mirror. See module's readme for more details.
CONFIGURATION OPTIONS
  The following properties can be configured:
    Option
      feeds
        Description - An array of feed urls that will be used as source.
                      More info about thsi object can be found below.
                      Default value: [{ title: "New York Times", url: "https://www.nytimes.com/services/xml/rss/nyt/HomePage.xml",encoding: "UTF-8" }]
                      You can add reloadInterval option to set particular reloadInterval to a feed.
      showAsList
        Description - Display the news as a list.
                      Possible values: true or false
                      Default value: false
      showSourceTitle 
        Description - Display the title of the source.
                      Possing values: true or false
                      Default value: true
      showPublishDate
        Description - Display the publish date of an headline.
                      Possible values: true or false
                      Default value: true
      broadcastNewsFeeds
        Description - Gives the ability to broadcast news feeds to all modules, by using sendNotification() when set to true, rather than sendSocketNotification()                       when false
                      Possible values: true or false
                      Default value: true
      broadcastNewsUpdates
        Description - Gives the ability to broadcast news feed updates to all modules
                      Possible values: true or false
                      Default value: true
      showDescription
        Description - Display the description of an item.
                      Possible values: true or false
                      Default value: false
      showTitleAsUrl
        Description - If set, the displayed title is a link to the article which is useful when running in a browser and you want to read this article.
                      Possible values: true ro false
                      Default value: false
      wrapTitle
        Description - Wrap the tile of the item to multiple lines.
                      Possible values: true or false
                      Default value: true
      wrapDescription 
        Description - Wrap the description of the item to multiple lines.
                      Possible values; true or false
                      Default value: true
      wrapDescription 
        Description - Wrap the description of the item to multiple lines.
                      Possible values: true or false
                      Default value: true
      truncDescription
        Description - Truncate description?
                      Possible values: true or flase
                      Default value: true
      lengthDescription 
        Description - How many characters to be displayed for a truncated description:
                      Possible values: 1-500
                      Default value: 400
      hideLoading
        Description - Hide module instead of showing LOADING status.
                      Possible values: true ro false
                      Default value: false
      reloadInterval 
        Description - How often does the content needs to be fetched? (Milliseconds)
                      Possible values: 1000 - 86400000
                      Default value: 300000 (5 Minutes)
      updateInterval
        Description - How often do you want to display a new headline? (Milliseconds)
                      Possible values: 1000 - 60000
                      Default value: 10000 (10 seconds)
      animationSpeed
        Description - Speed of the update animation. (Milliseconds)
                      Possible values:0 - 5000
                      Default value: 2500 (2.5 seconds)
      maxNewsItems
        Description - Total amount of news items to cycle through. (0 for unlimited)
                      Possible values: 0-...
                      Default value: 0
      ignoreOldItems
        Description - Ignore news items that are outdated.
                      Possible values: true or false
                      Default value: false
      ignoreOlderThan
        Description - How old should news items be before they are considered outdated? (Milliseconds)
                      Possible values: 1-...
                      Default value: 86400000 (1day)
      removeStartTags
        Description - Some news feeds feature tags at the begining of their titles or descriptions, such as [VIDEO]. This setting allows for the removal of                              specified tags from the beginning of an item's description andk/or title.
                      Possible values: 'title','description','both'
      startTags
        Description - List the tags you would like to have removed at the beginning of the feed item
                      Possible values: Possible vlaues: ['TAG'] OR ['TAG1','TAG2',...]
      removeEndTags
        Description - Remove specified tags from the end of an item's description and/or title.
                      Possible values: 'title','description','both'
      endTags
        Description - List the tags you would like to have removed at the end of the feed item
                      Possible values: ['TAG'] OR ['
                      
                      
