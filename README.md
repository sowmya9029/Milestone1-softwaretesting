
#Description:
Minimal ToDo is an android app where you can track your daily todos. With this app, you can create your own todo list and manage by setting date and time. Alogn with date and time, you can set reminder and snooze options for created todos.

# 2.1. Location of unit tests 
The local unit tests of an Android project are located in the `app/src/test` folder.

# 2.2. Required dependencies in the Gradle build file
  To use JUnit tests for your Android application, you need to add it as dependency to your Gradle build file.

      dependencies 
      {
         // Unit testing dependencies
         testImplementation 'junit:junit:4.12'
         // for testing core functionalities of android
         testImplementation 'androidx.test:core:1.0.0'
         // Optional -- Mockito framework
         testImplementation 'org.mockito:mockito-core:2.15.0'
      }


# 2.3. Running the unit tests
We are running Local Unit Tests in Android application for some units of two classes "ItemTouchHelperClass" and "ScrollingFABBehavior".Test uses mockito library to mock some of the Android framework objects. 

   ## 2.3.1. Using Gradle
      Run your unit tests with the "gradlew test" command.
   ## 2.3.2. Using Android Studio
      To run a unit test, right-click on your test class in the Project window and select Run.

# 2.4. Location of test reports
The Test reports are created in the `app/build/reports/tests/debug/` directory. The index.html gives an overview and links to the individual test pages.



