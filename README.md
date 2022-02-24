## monet-icons
XML files and a tutorial on how to modify Android apps to add themed icons to them.

# Using PC

To apply icons, first pull or download the apk file. After you have it saved, decompile the APK using apktool. After that, go to `res/drawable/` and add the .xml file corresponding to the app you want to add.
Next, navigate to `res/mipmap-anydpi-v26/ic_launcher.xml` and open the file. Near the end, add `<monochrome android:drawable="@drawable/themed_icon_app" /> (replace app with the name of the app you are modifying.
After you are done, recompile the app using apktool and add a new signature. Now uninstall the previous app (as signatures have been changed, and install your new apk.
