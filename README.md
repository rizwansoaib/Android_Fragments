# Android Fragments
## [Download APK](https://github.com/rizwansoaib/Android_Fragments/releases/download/v1/fragments.apk)
## Code
- [strings.xml](https://github.com/rizwansoaib/Android_Fragments/blob/master/app/src/main/res/values/strings.xml)
- [activity_main.xml](https://github.com/rizwansoaib/Android_Fragments/blob/master/app/src/main/res/layout/activity_main.xml)
- [fragment_one.xml](https://github.com/rizwansoaib/Android_Fragments/blob/master/app/src/main/res/layout/fragment_one.xml)
- [fragment_two.xml](https://github.com/rizwansoaib/Android_Fragments/blob/master/app/src/main/res/layout/fragment_two.xml)
- [MainActivity.java](https://github.com/rizwansoaib/Android_Fragments/blob/master/app/src/main/java/com/example/fragments/MainActivity.java)
- [FragmentOne.java](https://github.com/rizwansoaib/Android_Fragments/blob/master/app/src/main/java/com/example/fragments/FragmentOne.java)
- [FragmentTwo.java](https://github.com/rizwansoaib/Android_Fragments/blob/master/app/src/main/java/com/example/fragments/FragmentTwo.java)


In Android, the fragment is the part of Activity which represents a portion of User Interface(UI) on the screen. It is the modular section of the android activity that is very helpful in creating UI designs that are flexible in nature and auto-adjustable based on the device screen size. The UI flexibility on all devices improves the user experience and adaptability of the application. Fragments can exist only inside an activity as its lifecycle is dependent on the lifecycle of host activity. For example, if the host activity is paused, then all the methods and operations of the fragment related to that activity will stop functioning, thus fragment is also termed as sub-activity. Fragments can be added, removed, or replaced dynamically i.e., while activity is running. 

     
      <fragment> tag is used to insert the fragment in an android activity layout. By dividing the activity’s layout multiple fragments can be added in it.
      
      Each fragment has it’s own lifecycle but due to the connection with the Activity it belongs to, the fragment lifecycle is influenced by the activity’s lifecycle.
     
![image](https://github.com/rizwansoaib/Android_Fragments/assets/29729380/d1bd8f07-30cd-45ae-918a-d69220f5c7be)

![image](https://github.com/rizwansoaib/Android_Fragments/assets/29729380/e8086454-97cc-46d7-bac7-ac25e3186b9e)


| Methods	| Description |
| :---:   | :---: | 
| onAttach() |	The very first method to be called when the fragment has been associated with the activity. This method executes only once during the lifetime of a fragment. |  
| onCreate() |	This method initializes the fragment by adding all the required attributes and components.|
| onCreateView() |	System calls this method to create the user interface of the fragment. The root of the fragment’s layout is returned as the View component by this method to draw the UI.|
| onViewCreated()	| It indicates that the activity has been created in which the fragment exists. View hierarchy of the fragment also instantiated before this function call. |
| onStart()	|The system invokes this method to make the fragment visible on the user’s device.|
| onResume() |	This method is called to make the visible fragment interactive.|
| onPause() |	It indicates that the user is leaving the fragment. System call this method to commit the changes made to the fragment. |
| onStop() |	Method to terminate the functioning and visibility of fragment from the user’s screen. |
| onDestroyView() |	System calls this method to clean up all kinds of resources as well as view hierarchy associated with the fragment. |
| onDestroy() |	It is called to perform the final clean up of fragment’s state and its lifecycle. |
| onDetach() |	The system executes this method to disassociate the fragment from its host activity. |


## [References](https://www.geeksforgeeks.org/fragment-lifecycle-in-android/)

