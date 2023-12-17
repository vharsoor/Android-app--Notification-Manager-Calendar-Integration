This app helps you focus by blocking distracting notifications and organizes your tasks and events with a calendar.<br/>
INSTRUCTIONS TO EXECUTE/USE THE APP:
1) Generate OAuth 2.0 Credentials:<br/>
a) Create/Sign-in into Google Cloud console and enable Google Calendar API.<br/>
b) Generate OAuth credentials of the Web Application type, not Android.<br/>
c) During the configuration of the OAuth consent screen, ensure to enable the required scopes auth/calendar.readonly & auth/calendar) and specify the project name exactly as it is stated in the Android manifest. (Ex: package="com.example.proj5")<br/>
d) Utilize the Web Client ID obtained from OAuth and add/replace it in the "web_client_id" field in the strings.xml file.<br/>

2) Add/show events from the Google Calendar:<br/>
a) Enable all necessary permissions when the app is launched for the first time and sign into the corresponding Google account (following the prompt).<br/>
b) Navigate to the calendar page and click on "Recent Events" to display your recent events from Google Calendar.<br/>
c) On the page, to add an event, input the event summary/title along with the start date of the event (in the displayed format).<br/>

3) To cancel/block the notifications from the distracting apps based on a timer:<br/>
a) Enter the timer duration (in hours) and start typing the names of the apps from which you want to block notifications; a menu option will pop up for selection. b) If a non-integer value is entered in the timer, a toast error message will be displayed.<br/>
c) Entering valid values will initiate the timer, blocking notifications from the selected apps until the timer expires.<br/>
d) The UI displays the remaining timer duration and the list of blocked apps.<br/>

All the libraries required are included in the android Project.

<img src="https://github.com/vharsoor/Android-app--Notification-Manager-Calendar-Integration/assets/70684031/9c49329c-13ed-4808-a7af-f6f1629ca542" width="110" height="240">
<img src="https://github.com/vharsoor/Android-app--Notification-Manager-Calendar-Integration/assets/70684031/59c4e66f-4597-4f8e-95eb-154410a762d1" width="110" height="240">

