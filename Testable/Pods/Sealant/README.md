Sealant is iOS Testing Glue
=======

Fixtures, Matchers and Helpers packaged into one [Cocoa Pod](http://cocoapods.org).
Testing iOS apps and Cocoa code is still hard, some little magic helps.
Sealant connects testing libraries with libraries used by code under test.

Installation
-------

Use [Cocoapods](http://cocoapods.org) to install Sealant:


> target :spec, :exclusive => true do

>    pod 'Sealant'

> end

The above installs minimal generic set of utilities without any dependencies. To install full set specify:

> pod 'Sealant/Kiwi'

> pod 'Sealant/MKNetworkKit'

Example
------

[Testable](https://github.com/blazingcloud/sealant/tree/master/Testable) is Xcode Project example that uses Sealant. 
Please review [Best practices](https://github.com/blazingcloud/sealant/tree/master/Testable/ReadMe.md) of setting up new Xcode projects with testing tools like:
*   [Kiwi](https://github.com/allending/Kiwi)
*   [Hamcrest](http://code.google.com/p/hamcrest/wiki/TutorialObjectiveC)
*   [KIF](https://github.com/square/KIF)

Documentation
------

Documentation is on [Wiki](/blazingcloud/sealant/wiki)
