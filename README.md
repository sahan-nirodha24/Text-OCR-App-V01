## 📋📷 Text OCR App Version 01 📸📄

The **Text OCR App** is an Android application that utilizes **Google ML Kit** to recognize and extract text from images. This app captures an image using the device's camera, processes the image to extract any text using Optical Character Recognition (OCR), and then displays the recognized text on the screen. The user can then copy the recognized text to the clipboard or reset the interface.

### Features

+ **Capture Image:** Use the device's camera to capture an image.
+ **OCR Text Recognition:** Extract and display text from the captured image.
+ **Text Scrolling:** The recognized text can be scrolled if it exceeds the viewable area.
+ **Copy Text:** Copy the recognized text to the clipboard with a single click.
+ **Reset:** Clear the image and reset the app to its initial state.
+ **Splash Screen:** Displays a splash screen with a progress bar, showing the app's initialization progress from 0% to 100%.


### How It Works

- **Splash Screen:** Upon launching the app, the splash screen is shown with a progress bar indicating the initialization process, which progresses from 0% to 100%.
  
- **Capture Image:**
   + The user clicks the "Capture" button to take a photo using the device’s camera.
   + The app requests camera permission if it’s not granted.
   + Once permission is granted, the user can capture an image, and the image is displayed in an ImageView.
    
- **Text Recognition:**
   + Once the image is captured, the app processes it using Google ML Kit’s text recognition API.
   + The recognized text is displayed in a scrollable TextView for better readability.
     
- **Copy Text:**
   + The user can copy the recognized text to the clipboard by clicking the “Copy” button.
   + A toast message appears confirming that the text has been copied.

- **Reset:**
   + The user can reset the app to its initial state by clicking the “Clear” button.
   + The app will clear the displayed text, hide the "Copy" and "Clear" buttons, and reset the image to a default placeholder.



  



