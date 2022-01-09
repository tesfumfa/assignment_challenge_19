# Assignment_challenge_19
<h1>Budget-Tracker-PWA</h1>
<h2>Table of Contents</h2>
<ul>
  <li> <a href="#"> Task</a></li>
   <li> <a href="#"> Description</a></li>
  <li> <a href="#"> User Story</a></li>
  <li> <a href="#"> Acceptance Criteria</a></li>
</ul>

<h2>Task</h2>
<p>
  Giving users a fast and easy way to track their money is important, but allowing them to access that information at any time is even more important. Having offline functionality is paramount to the success of an application that handles users’ financial information.

My challenge this week is to update an existing budget tracker application to allow for offline access and functionality. The user will be able to add expenses and deposits to their budget with or without a connection. If the user enters transactions offline, the total should be updated when they're brought back online. Once I’ve made these changes, I’ll deploy the application to Heroku.
</p>
<h2> Description</h2>
<p>
For this challenge, I was tasked with updating a simple budget tracking application to allow for offline access and functionality. The user will be able to record expenses and deposits to their budget app with or without an internet connection. Offline transactions are updated to the app when the user returns back online.

The application’s front end has already been created. It's my job to add offline persistence with IndexedDB, implement PWA functionality, and then deploy the finished application to Heroku via local  MongoDBCompass.

</p>
<h2>User Story</h2>
<p>
  AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling
</p>
<h2>Acceptance Criteria</h2>
<p>
  GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated
</p>
<h2>Website Link</h2>
<a href="https://assignment-challenge-19.herokuapp.com/"> Budget Tracker </a>

