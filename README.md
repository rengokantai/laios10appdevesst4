# laios10appdevesst4
##1 iOS Application Architecture

###2 Foreground and background events
order:  
didFinishLaunchingWithOptions->applicationDidBecomeActive  

go to home, shift cmd h  
applicationWillResignActive->applicationDidEnterBackground

return to the program,  
applicationWillEnterForeground->applicationDidBecomeActive  

terminate the app shift cmd h (hold these 3 button twice)  



###3 View events
ViewCOntrller.java for main methods
```
viewDidAppear
viewWillAppear
viewDidDisappear
viewWillDisappear
```
###4 Background tasks
Capabilities background modes ->on

###5 Debugging view hierarchies
####02:32
If you click this button in the middle at the bottom you can show the clip to views.
So you can see that some of the views are being clipped for a switch
###6 How to use the debugger
cmd b ->build
