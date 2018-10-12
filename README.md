# codefundoo-safeKit
Android application to help users during severe weather conditions. 

## Team Details 
**Team name** : <br />
w00tw00t <br />
**Members** : <br />
Ujjval Goury <br />
Manaswi Rajpurohit

## Idea
It is an android (more outreach) application to help users during severe weather conditions. This app will support following features: <br />
* Alert the user beforehand of any natural disaster warming in his/her region. 
* Provide the contacts of near-by hospitals, fire-station to users.
* One-button feature to share *contact information and location* of the user to the nearby emergency wards and other users by voice-synthesised calls (made by the server) in case the person is panicked
* Feature for users to report bad weather, which may deploy the alert protocols even if it is not predicted by the server.
* Provide users with regular safety tips about calamities prone to the particular area

In this we will use apis (oneweatherapp and destination weather) which will inform about weather conditions of a particular location and also about alerts. This data will be used to alert users using their location if there is an alert raised in that location. The database for emergency numbers (of hospitals and fire stations) will be accessed through government site data.gov.in.
The data of all users will be stored in the azure database. We will build a machine learning model which will be trained using neural network  with features like rainfall, windspeed, coordinates to predict calamity. 


