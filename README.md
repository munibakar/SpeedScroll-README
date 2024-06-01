# Installation
Follow the steps below to run this project on your local machine.
## 1. Installing Required Tools
Before you start working on the project, make sure you have the necessary tools installed on your system:
#### Flutter SDK
Follow the instructions on [Flutter's official website](https://flutter.dev/docs/get-started/install) to install Flutter SDK.
#### Android Studio
Download and install Android Studio [here](https://developer.android.com/studio). Make sure you install Flutter and Dart plugins:
1. Open Android Studio.
2. Go to File > Settings > Plugins menu.
3. In the Marketplace tab, search for Flutter plugin and install it. This will automatically install the Dart plugin as well.
#### Visual Studio Code (Optional)
Download and install Visual Studio Code [here](https://code.visualstudio.com/). Then install Flutter and Dart plugins:
1. Open VS Code.
2. Go to the Extensions menu (Ctrl+Shift+X).
3. Search for Flutter plugin and install it. This will automatically install the Dart plugin as well.
   <br/>
   <br/>
   
## 2. Clone the Project
Download the project to your local machine by cloning the GitHub repository:
bash
git clone https://github.com/USERNAME/REPOSITORY_NAME.git
cd REPOSITORY_NAME 

<br/>
<br/>

## 3. Install Dependencies
Run the following command in terminal to install Flutter dependencies:
bash
flutter pub get

<br/>
<br/>

## 4. Set API Keys
To add API keys, follow these steps:
1. Go to the file named map_page.dart in the lib/screens/ directory.
2. Set the contents of the map_page.dart file as follows:
bash
Future<void> _getDirections() async {
    String apiKey =
        "YOUR_GOOGLE_MAPS_API_KEY "; // Google Directions API key

<br/>
<br/>

## 5. Run the App
#### Android Studio Emulator
Open Android Studio and create a virtual device via AVD Manager:
1. Open Android Studio.
2. Go to Tools > AVD Manager menu.
3. Click Create Virtual Device.
4. Select a device and continue by clicking Next.
5. Select a system image and continue by clicking Next.
6. Make the necessary configurations and create the emulator by clicking Finish.
#### Running the App in Emulator
To run the Flutter app on the emulator, use the following command in the terminal:
bash
flutter run

#### APK Installation (Direct to Device)
If you have an Android device, you can install the APK file directly on the device. To do this, follow these steps:
1. In the root directory of your project, navigate to the build/app/outputs/flutter-apk folder.
2. Find the app-release.apk file.
3. Connect your Android device to your computer with a USB cable.
4. Copy the file to your device.
5. Finally, find and open the file on your device and install it.
