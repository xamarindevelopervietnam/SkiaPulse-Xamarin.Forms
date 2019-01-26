# SkiaPulse-Xamarin.Forms
Pulse animation for xamarin forms based on SkiaSharp

------------


![](https://raw.githubusercontent.com/abdulrahmanelfeky/SkiaPulse-Xamarin.Forms/master/appVideo.gif)

------------


![](https://raw.githubusercontent.com/abdulrahmanelfeky/SkiaPulse-Xamarin.Forms/master/skiapulse_screenshot.png)

------------


# Compatibility 
- Xamarin.Forms

------------


# Quickstart 
##### Xml
           <SkiaPulse:Pulse AutoStart="true" PulseColor="#8e44ad" Margin="50" Speed="10" Source="SkiaPulse.Images.wifi_icon.png"  />

Use an image resource as an Embedded Resource
Do not add the image as a resource.  would rather do the following:

    Create the image/icon and save it to a file
    Choose Shared Project -> Add Existing Item and add the file
    Set the Build Action to Embedded Resource

# Dependencies
- SkiaSharp
- SkiaSharp.Views
- SkiaSharp.Views.Forms
