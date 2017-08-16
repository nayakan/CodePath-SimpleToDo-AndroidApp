# SimpleToDo_AndroidApp

SimpleToDo is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by Akshatha Nayak
Time spent: 2.5 hours spent in total

## User Stories

Completed User Stories:

* [YES] User can **successfully add and remove items** from the todo list
* [YES] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list.
* [YES] User can **persist todo items** and retrieve them properly on app restart

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![todoapp_demo](https://user-images.githubusercontent.com/17459420/29349470-f2048ed8-820e-11e7-82f2-da2e111c9395.gif)


## Project Analysis

As part of your pre-work submission, please reflect on the app and answer the following questions below:

**Question 1:** "What are your reactions to the Android app development platform so far? Compare and contrast Android's approach to layouts and user interfaces in past platforms you've used."

**Answer:**
This was my first time building an Android application and it sure seemed fun. In the process of building this app I got oriented about the development enviroment, code constructs, limitless possibilities of application development.

**Question 2:** "Take a moment to reflect on the `ArrayAdapter` used in your pre-work. How would you describe an adapter in this context and what is its function in Android? Why do you think the adapter is important? Explain the purpose of the `convertView` in the `getView` method of the `ArrayAdapter`."

**Answer:** 'ArrayAdapter' provides views for a collection of objects: For each item/object in a collection of items/objects provided the ArrayAdapter creates a view and it useful in our application for listing todo items in the ListView.
Adapter acts as a bridge between views/UI and underlying data. They provide a means to provide/control display of data.
'convertView' helps avoid instantiating a new object everytime when adapter wants to display a list item, by recycling old view objects.


