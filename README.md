# Paul Dardis – BT Ireland 
## User-Centric Frontend Development Milestone Project

### Demo
A live demo can be found [here](https://pauldardis.github.io/User-Centric-Milestone-Project/index.html)

### Purpose 
This is a fully responsive website designed to showcase the cycling tours organised by Donadea Wheelers cycling club. 

The primary target audience is members of Donadea Cycling club who wish to travel and are looking for information on upcoming tours. 

The secondary audience is members of other local cycling clubs who may want to join or keep a track on our tours and routes. 


## UX
### Background 
Since 2012 I have been organising tours for my cycling club they have become more and more successful and we have started to get requests from members of other cycling clubs to join our tours as a result I was getting constant requests  by phone, email, etc for basic information.  This website is being set up to organise and promote tours and to act as central point of information.

### Website Requirements 
#### High Level Requirements 
1.	Inform users of upcoming tours 
2.	Inform users of routes on tours so that they judge fitness level needed. 
3.	Allow users to book places on upcoming tours.
4.	Allow users to request more information on tours. 
5.	Allow users to access Cycle Tours social media pages 
6.	Allow users to subscribe to Newsletter
7.	Will be responsive and work on all devices 
8.	Allow users to navigate easy from one section to another

#### User Stories 
--------------------------------------------------------------------------------------------------------------------------------------------------
|No.|	User Type   |	What I want to do                                               |Why I want to do it                                        |
----|---------------|-----------------------                                            | -------------------------------------------------------   |
|1|	DW Club Member  |I want to find the  dates and destination of the next tour         |                                                           | 
|2|	DW Club Member  |Understand what’s included / excluded in the tour                  |To see if the tour is value for money                      |
|3| DW Club Member  |See the route                                                      |To see the fitness level required                          |
|4|	Public          |Know the team behind the tours                                     |                                                           |
|5|	Public          |Subscribe to a newsletter                                          |To be kept up to date on future tours                      |
|6|	All             |Make a booking                                                     |                                                           |
-----------------------------------------------------------------------------------------------------------------------------------------------------


### Features
#### Home Page
There are 3 card features displaying the current 3 tours. These cards hold images of the trip and provide a brief description of the tour. There is a button which will allow the user to click which will bring them to the relevant tour page. Currently we only plan 3 tours per year this may change in future years and we will add more cards into the main page. 

Newsletter subscription service

![Home page](/assets/images/home.JPG)

#### About Page
Allows the user to get a brief description of the company and also the team running the tours. 

The team section is designed in a zig-zag layout to make it more visual 

Newsletter subscription service 

![About page](/assets/images/about.JPG)

#### Destination pages (Mallorca, Pyrenees and Alps) 
Brief description of the tour 

Provide information on what’s included / excluded also the cost and prices. 

A day 2 day Itinerary

Information on the distance each day and also the amount of meters climbed. 

Video of the daily route  (currently not available for the Alps and will be added in September once the tour is completed so it will be available for future tours) 

Gallery of phots taken during the tour. 

Newsletter subscription service 

![Destination page](/assets/images/destination.JPG)

![destination itinerary video](/assets/images/destination2.JPG)

![Destination galery](/assets/images/destination3.JPG)

#### Contacts 
Form to allow a user to contact us and request more information (this information doesn’t go anywhere at the moment). 

A google map to show were we are located.  

A newsletter subscription service 

![Contact Page](/assets/images/contact.JPG)

#### Booking 

A booking form that allows a user to request more information or provisionally book a place on a future trip. 

Tick box to confirm that the user agrees to wear a helmet during the tour. 

Tick box to subscribe to the newsletter

![Booking Page](/assets/images/booking.JPG)

### Technologies Used
1.	HTML
2.  CSS
3.  Javascript
4.  Bootstrap
5.  Font Awesome
6.  Cloudfare
7.  Goole Fonts 
8.  AutoPrefixer
9.  Github
10. Google Chrome Developer Tools
11. Gimp
12. Balsamiq
13. https://validator.w3.org/
14. https://jigsaw.w3.org/css-validator/
 
### Testing 

#### General Testing (all pages) 
1.	Go to Home Page 
2.	Verify that all links, icons, images and content are appearing correctly. 
3.	In top navigation bar, hover over each link and verify that the hover affects are working correctly (background colour to #da2a3a and font colour to #FFFFFF).
4.	In the footer, hover over each social icon and verify that the hover affects are working correctly (background colour to #da2a3a).
5.	In top navigation bar click on “About” and confirm it brings to the correct page. 
6.	In top navigation bar click on “Destinations” and confirm it shows a dropdown menu.
7.	In top navigation bar click on “Destinations” and “Mallorca” and confirm it brings to the correct page.
8.	In top navigation bar click on “Destinations” and “Pyrenees” and confirm it brings to the correct page.
9.	In top navigation bar click on “Destinations” and “Alps” and confirm it brings to the correct page.
10.	In top navigation bar click on “Contact” and confirm it brings to the correct page.
11. In Newsletter email enter an invalid email address (without the @) can confirm it returns an error when the subscribe button is pressed. 
12. In Newsletter email enter a valid email address can confirm no error is returned when the subscribe button is pressed.
13. In the footer click on each social media link and confirm that a new page is opened and confirm it brings you to the correct page 
14. In the footer click on the email address and confirm it opens up your default email application on your device. 

#### Home Page
1.	In the destination cards hover over each image and text and confirm that the hover affects are working correctly (card show a shadow)
2.	In the destination cards hover over each button and verify that the hover affects are working correctly (background colour to #da2a3a and font colour to #FFFFFF).
3.	In the destination cards click each button and confirm it brings to the correct page.
4.	Using the Inspect functionality in Chrome confirm that page is responsive across all devices. 
5.	Using the w3.org validator confirm that there are no errors in the html

#### About Page
1.	Using the Inspect functionality in Chrome confirm that page is responsive across all devices. 

#### Mallorca Page
1.	Hover over the “Check Availability” link and verify that the hover affects are working correctly (background colour to #da2a3a and font colour to #FFFFFF).
2.	Click on the “Check Availability” link and conform that it brings you to the “Booking Page”. 
3.	Hover across each bar in the Itinerary and confirm that the hover affects are working correctly. 
4.	Click on each bar and conform that they expand down , 
5.	Re-click on each bar and confirm that the collapse back into a closed state
6.	Click on the embedded video and confirm that it plays correctly. 
7.	Confirm that all images a lined up correctly in Photo Gallery 
8.	Using the Inspect functionality in Chrome confirm that page is responsive across all devices. 

#### Pyrenees Page
1.	Hover over the “Check Availability” link and verify that the hover affects are working correctly (background colour to #da2a3a and font colour to #FFFFFF).
2.	Click on the “Check Availability” link and conform that it brings you to the “Booking Page”. 
3.	Hover across each bar in the Itinerary and confirm that the hover affects are working correctly. 
4.	Click on each bar and conform that they expand down , 
5.	Re-click on each bar and confirm that the collapse back into a closed state
6.	Click on the embedded video and confirm that it plays correctly. 
7.	Confirm that all images a lined up correctly in Photo Gallery 
8.	Using the Inspect functionality in Chrome confirm that page is responsive across all devices. 

#### Alps Page
1.	Hover over the “Check Availability” link and verify that the hover affects are working correctly (background colour to #da2a3a and font colour to #FFFFFF).
2.	Click on the “Check Availability” link and conform that it brings you to the “Booking Page”. 
3.	Hover across each bar in the Itinerary and confirm that the hover affects are working correctly. 
4.	Click on each bar and conform that they expand down 
5.	Re-click on each bar and confirm that the collapse back into a closed state.
6.	Confirm that all images a lined up correctly in Photo Gallery 
7.	Using the Inspect functionality in Chrome confirm that page is responsive across all devices. 

#### Contact Page
1.	Hover over the “Send Message” link and verify that the hover affects are working correctly (background colour to #da2a3a and font colour to #FFFFFF).
2.	Incorrectly fill out form by leaving out information or inputting invalid information, confirm that error message is sent when “Send Message” link is pressed. 
3.	Click on “View Larger Map” on Google Map and confirm new webpage is opened and displayed correctly 
4.	Using the Inspect functionality in Chrome confirm that page is responsive across all devices. 

#### Booking Page
1.	Hover over the “Send Message” link and verify that the hover affects are working correctly (background colour to #da2a3a and font colour to #FFFFFF).
2.	Incorrectly fill out form by leaving out information or inputting invalid information, confirm that error message is sent when “Send Message” link is pressed. 
3.	Using the Inspect functionality in Chrome confirm that page is responsive across all devices. 

#### Testing issues and observations
1.  Intermittently images are not downloading fast enough as a result text is visable first and then its pushed down by the image. I have reduced down all image’s  file size using https://tinyjpg.com/ however it has made no difference.  Using pingdom.com I now believe the issue is being caused by “fontawesome” its taking on average 566ms to load. A fix for this issue will be applied in the next phase of this website one possible solution is to load fontawesome via javescript.

![Speed Issue](/assets/images/speedissue.JPG)

2.  The main image on each page is responsive however if you zoom the web browser down to 50% (Ctrl -) a gap is created on the right hand side. I have gone through the configuration many times and I’m unable to find the root cause. The only way I have been able to resolve the issue is by increasing the file size however this is not a proper fix. I will continue to investigate the fault and hope to have a fix in the next phase of the website.
 
![Image Gap](/assets/images/imagegap.JPG)

3. When I fixed the Navbar at the top of the page the image is moving to the top of the body of the page as a result the image is being clipped.  To date I have been unable to resolve the issue however I have put in a temporary fix to minimise the issue, in the ccs file under .main-image-gap I have added padding-top: 3em; this pushes  down to an acceptable level however it still is slightly behind the navbar. I have tried adjusting the size of the padding however if it goes above 3em it cause a gap when viewed on a mobile. I will continue to investigate the fault and hope to have a fix in the next phase of the website.

![Navbar Issue](/assets/images/navbarissue.JPG)




### Deployment
To run locally, you can clone this repository directly into the editor of your choice by pasting git clone https://github.com/pauldardis/User-Centric-Milestone-Project into your terminal. To unlink the site from the GitHub repository, type git remote rm origin into the terminal.
The site is hosted on GitHub and can be run from there or locally by pasting the following link directly into your browser. https://pauldardis.github.io/User-Centric-Milestone-Project/index.html
To view the source code please click on the following GitHub address https://github.com/pauldardis/User-Centric-Milestone-Project


### Future Developments
1.  Resolve the issues that were highlighted during the testing in phase 1.
2.  Image modal on the destination pages to allow a user to see the gallery images in full screen.
3.  Backend system to allow users to subscribe to a newsletter.
4.  Backend system to allow users to capture information from contact form.
5.  Functionally to allow users to register and login to view private pages. 


### Credits

#### Content
Images for alps.html were taken from Band of Climbers website https://www.bandofclimbers.com/ 
All other images were privately owned. 

#### Video
Video routes were provide by https://www.relive.cc/ and were developed from my own Strava uploads.

#### Photos
Images for alps.html were taken from Band of Climbers website
All other images were privately owned. 

#### Code Snippets 
Newsletter signup snipit was got from Bootsnipp.com (https://bootsnipp.com/snippets/eoXRa)

Collapsible section in mallorca.html alps.html and pyrenees.html was got from w2schools.com (https://www.w3schools.com/howto/howto_js_collapsible.asp) 

Contact form snipit was got from bootsnipp.com (https://bootsnipp.com/snippets/zD4p9) 

All code snipits were modified to suit the website

#### Testing Tools
1.  https://validator.w3.org/
2.  https://jigsaw.w3.org/css-validator/
3.  https://tools.pingdom.com/


#### Development Tools
1.  https://tinyjpg.com/ used to reduced down the file size of the images.
2.  Gimp https://www.gimp.org/ image manipulation program
3.  Adobe Color https://color.adobe.com/create 


### Disclaimer:
This project was created for educational use.



















 


