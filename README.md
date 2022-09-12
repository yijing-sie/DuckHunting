# DuckHunting

This is an assignment for Software Design for Visual Environments

* The goal is to build a **game** application where users shoot from a cannon at a duck flying across the screen

* [duckhuntingv3](java/com/jblearning/duckhuntingv3) folder contains all my Java files
* [res](res) folder contains the imgages and xml files for the UI of this application
* [MainActivity.java](java/com/jblearning/duckhuntingv3/MainActivity.java) implements the animation of a flying duck by using the [GameTimerTask](java/com/jblearning/duckhuntingv3/GameTimerTask.java) class to update the state of the game every **100 milliseconds**
* [GameView.java](java/com/jblearning/duckhuntingv3/GameView.java) implements `GameView` class that draws all the objects: **canon**, **bullet**, and **duck** for the game
* [Game.java](java/com/jblearning/duckhuntingv3/Game.java) detects **multiple taps** and **swipes** from users to move the cannon barrel and launch a shooting

There are **4** features in this application:
1. The duck starts at a random height everytime 
2. Users can use a **single tap** or **swipe** the screen to change the angle of the cannon barrel
3. Users can **double tap** anywhere on the screen to launch a shooting at the point where the cannon barrel is pointing 
4. When the duck is hit, a small **quack** sound is played; moreover, whenver users fire a bullet, a **gun shut** sound is played as well

Below is the demonstration of the game

https://user-images.githubusercontent.com/84282744/189731757-8a45faba-e214-4069-b2cc-5faa757ebc39.mp4

