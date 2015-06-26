# RootBeer

A tasty root checker library and sample app. We've scoured the internets for different methods of assessing has this device got root? and added some of our own checks. 


#Checks
Native checks are typically harder to cloak, so some root cloak apps just block the loading of native libraries that contain certain key words.. RootCheck is one! so you might want to change the native lib name. 

**Java checks**

* CheckRootManagementApps
* CheckPotentiallyDangerousAppss
* CheckTestKeys 
* checkForDangerousProps
* checkForBusyBoxBinary
* checkForSuBinary
* checkSuExists
* checkForRWSystem
* CheckRootCloakingApps

**Native checks**
 
* checkForSuBinary


##Disclaimer and limitations!

We love root! both [Scott](https://github.com/scottyab) and [Mat](https://github.com/steathcopter) (the main contributors) use rooted devices. But we appreciate sometimes you might want to have a indication your app is running on a rooted handset. Plus we wanted to see if we could beat the root cloakers. So that's what this library gives you, an *indication* of root. 

Remember **root==god**, so there's no 100% way to check for root.

TODO picture of god/jesus drinking root beer i.e http://www.purederry.com/wp-content/uploads/2014/04/buddy-beer-jesus.jpg


### Root cloakers
Rootbeer can be defected but some of the root cloaks apps in combienation with xposded / cyida frameworks.

Tested cloakers

TODO list


##Usage

TODO


###Dependency

```java
dependencies {
    compile('com.scottyab:rootbeerlib:0.0.1')
}
```
### Sample app

TODO screen shot and link to play store

##Contributing

There must be more root checks to make this more complete. If you have one please do send us a pull request.



##Other libraries
 If you dig this, you might like:
 
 * Tim Strazzere's [Anti emulator checks](https://github.com/strazzere/anti-emulator/) project
 * Scott Alexander-Bown's SafetyNet Helper library - coupled with server side valdiation this is one of the best root detection approaches

#Licence


Apache License, Version 2.0



    Copyright (C) 2015, Scott Alexander-Bown, Mat Rollings

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

         http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

