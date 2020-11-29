# HubitatCustom
# Super Parameter Setting Tool

This is a parameter setting tool that uses the device's manufacturer, device type, and device ID information to retrieve parameter setting information from a dabase.

This is still a work-in-progress.

Some tips:
* Install the driver on the "Driver Code" page. I twill appear with the name "Super Parameter Setting Tool"
* Go to the device that you want to work on and select this tool as its driver.
* Click on the "Initialize" control to pull the data from the database and to poll your device for its current parameter settings.
* The "Preferences" area should now show controls for all of the parameters.  If everything worked right, the controls should show the current settings of your device
* You should now be able to change / udpate the parameters.
* Before switching back to your original driver, you can click on the "Uninstall" button to clean the State Variable data if you want to remove it.



# Universal Z-Wave Driver 

This is a device driver (dimmers & switches mostly) that will incoprorate the features of the Super Parameter Setting tool.

This is still in "beta" and isn't ready for general use. I'll update this page with some more information once I get time to develope it further.