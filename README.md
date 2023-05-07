# DRINK WATER APP

#### Video Demo: <URL HERE> // added only for cs50 staff

#### Description:

The given project is a water drinking app built using HTML, CSS, and JavaScript, with the help of the LocalStorage API. The purpose of the app is to help users track their daily water intake with a goal of consuming 3 liters of water per day.

Description:
The app provides a simple user interface that consists of a large cup representing the user's daily water intake goal and multiple small cups representing individual glasses of water, each with a capacity of 250 ml. Users can select the number of glasses they have consumed by clicking on the small cups. The app will then visually fill the large cup according to the total water intake.

As the user clicks on the small cups, the percentage of the daily goal reached will be displayed inside the large cup, along with an emoji indicating the user's progress towards their daily goal. The app also displays the remaining water intake needed to achieve the daily goal in liters.

The app uses JavaScript for its core functionality. Small cups are highlighted based on user interaction and the large cup is updated accordingly. The app utilizes the LocalStorage API to save the user's progress, so their water intake is preserved even when the browser is closed or refreshed.

Key Functions:

1. highlightCups(idx): This function highlights the small cups based on the index passed as an argument, indicating the number of glasses consumed.
2. updateBigCup(): This function updates the large cup's display, including the percentage of the goal reached, the emoji, and the remaining water intake.
3. updateLS(): This function updates the local storage with the current number of full small cups.
4. loadLS(): This function loads the saved progress from local storage and updates the app interface accordingly.

Overall, this water drinking app provides a visually appealing and intuitive way for users to track and monitor their daily water consumption, encouraging them to achieve their hydration goals.
