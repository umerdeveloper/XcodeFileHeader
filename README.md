# XcodeFileHeader
How to change Xcode file header?

Steps to follow:
1. Right click on projectName.xcodeproj
2. Click on **Show Package Contents**
3. Make directory there with name **xcshareddata**
4. Use this plist [Plist File](https://github.com/umerdeveloper/XcodeFileHeader/blob/main/IDETemplateMacros.plist)
5. Change value to any string which you wanna add in file header
6. Next time when you will create new file in Project that string will appear as header

**Example:**
Three underscores will be replaced by Xcode internal values for example date, username etc

1. ___PACKAGENAME___
2. created by ___FULLUSERNAME___ on ___DATE___
