# Introduction to Android UI Testing

The application was created for improving skills (from the very beginning) in testing Android application use Espresso framework. Each screen contains UI elements which are used by many applications. 

<p align="center">
  <img src="/art/screenshots/login_screen_framed.png" height="500" />
  <img src="/art/screenshots/home_screen_framed.png" height="500" />
  <img src="/art/screenshots/settings_screen_framed.png" height="500" />
</p>

This is the first application from the workshop "Creating Robust UI tests in Android" which allows everyone to learn the basics of Espresso:
* How to test separate screen in Android application
* How to interact with Android Views
* How to verify Settings screen in Android application
* How to create custom matchers and work efficiently with Espresso framework
* How to create custom actions which allow interacting with child view

# Structure of the project
The project has two main branches
* master
* solutions

The **master** branch has failed test cases which should be created from scratch. 
Each test case has a comment with a description of the test case and a hint (what can be used for implementing it).

The **solutions** branch has solutions for all test cases.

***Note:** In case if any of description is not understandable, please create an issue.*  

# App screens with views
**Login screen**
<p align="center">
  <img src="art/screens-with-views/login-screen.png" width="800" />
</p>

**Home screen**
<p align="center">
  <img src="art/screens-with-views/home-screen.png" width="800" />
</p>

**Settings screen**
<p align="center">
  <img src="art/screens-with-views/settings-screen.png" width="800" />
</p>

# Resources
* Espresso
    * [Official documentation](https://developer.android.com/training/testing/espresso)
* Hamcrest matcher
    * [Official documentation](http://hamcrest.org/JavaHamcrest/)
    * [Matchers](http://hamcrest.org/JavaHamcrest/javadoc/1.3/org/hamcrest/Matchers.html)
* UI Testing Tools
    * **UiAutomator Viewer**
        * [Documentation](https://developer.android.com/training/testing/ui-automator#ui-automator-viewer)
        * [Video Tutorial](https://www.youtube.com/watch?v=XBhfYAYKZF4)
    * **Layout Inspector**
        * [Documentation](https://developer.android.com/studio/debug/layout-inspector)
        * [Video Tutorial](https://www.youtube.com/watch?v=3out6Eh_DmQ)
    * [Comparing *UiAutomator Viewer* and *Layout Inspector*](https://alexzh.com/2018/12/10/efficient-testing-android-app-tools/)