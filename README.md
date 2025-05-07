# SwiftNotes
Useful Topic for Swift

What is a Property List (.plist)?
The Property List or .plist
.plist is short for Property List and it’s a file that’s automatically created with every Xcode project. This file stores configuration information for the application at runtime (when the app is running). The information is stored in a format called a key-value pair. Similar to a dictionary, the key is the property name and the value is the configuration.
For example, when we set the status bar as “light” in the general settings pane, a property is automatically created in the .plist with
key = Status bar style, value : String = UIStatusBarStyleLightContent.
