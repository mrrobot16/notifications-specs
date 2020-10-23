# Notifications Specs for proposal

Specs needed for us to make a proposal of this project.

### User Story

The user from an iOS app(that is already been built with React Native) will be able to set up thru checkboxes 4 types of notifications, by sending to our backend 
which of the 4 types notifications the user will like to receive and the expo.io push notification token(this token is needed 
and sent our to our backend onces user accepts which notifications would like to receive).

#### 4 types of notifications

For this project we expect to achieve 4 types of push notifications:
- Anticonceptive or contraception pill reminder.
- Highest Ovulation day reminder.
- High fertility days(range of days) reminder.
- Low fertility days(range of days) reminder.

For each notification we rely on several data inputs.

- Anticonceptive requires a time input (ie: 8:00 PM) for when the reminder should be trigger.

- Highest Ovulation requires the last day of when the user inputed a period log(this notification does not need time input).

- High Fertility requires the last day(startDate) of when the user inputed a Period Log in order to calculate the range of days 
in which user is in a current High Fertility(this notification does not need time input).

- Low Fertility requires the last day(startDate) of when the user inputed a Period Log in order to calculate the range of days 
in which user is in a current Low Fertility(this notification does not need time input).


#### Models

Period Log Model
- startDate: string
- endDate: string
- userID: string

#### Tech Stack requirements

- Client-side: React Native with [Expo](https://expo.io) this has already been built
- Server-side: Node.js [Express.js](https://expressjs.com/) or [Firebase cloud functions](https://firebase.google.com/docs/functions)
- Database: Firebase

#### Application we are cloning

Google Play: [https://play.google.com/store/apps/details?id=org.iggymedia.periodtracker&hl=en&gl=US](https://play.google.com/store/apps/details?id=org.iggymedia.periodtracker&hl=en&gl=US)

App Store: [https://apps.apple.com/us/app/flo-my-health-period-tracker/id1038369065](https://apps.apple.com/us/app/flo-my-health-period-tracker/id1038369065)


#### Submission

This proposal can be written in spanish.
Use a google document to write the proposal.

#### Further Help

Please reach out to me if you have any questions.

Happy Research :).