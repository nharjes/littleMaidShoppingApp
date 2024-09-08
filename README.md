# Little Maid Shop - Shopping Cart App

This is a simple shopping list web application using HTML, CSS, JavaScript, and Firebase Realtime Database. The app allows users to add and remove items to/from a shopping list, which is stored and synced using Firebase.

## Features

- Add items to a shopping list.
- Remove items from the shopping list by clicking on them.
- Stores data in Firebase Realtime Database, so the shopping list is persistent across sessions.
- Displays a message when the list is empty.

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Firebase Realtime Database

 ## Screenshot

![image](https://github.com/nharjes/littleMaidShoppingApp/blob/main/screenshot%20littleMaid.JPG)

## Firebase Configuration

The app uses Firebase Realtime Database to store and manage the shopping list. Make sure to replace the Firebase configuration with your own project settings.

```javascript
const appSettings = {
  databaseURL: "YOUR_FIREBASE_DATABASE_URL",
};
```
  ## License 
  This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
