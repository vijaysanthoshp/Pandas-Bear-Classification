# Pandas and Bears Classification

This is a Flutter application that uses TensorFlow Lite to classify images of pandas and bears. The app allows users to either take a photo using their device's camera or select an image from their photo gallery. Once an image is selected, the app will analyze it and provide a classification along with the confidence level.

## Features

- Splash screen with a animated gradient background and app logo
- Option to take a photo using the device's camera or select an image from the photo gallery
- Image classification using TensorFlow Lite
- Display of the classified label and confidence level
- Reset button to clear the selected image
- About section with information about the app

## Requirements

- Flutter SDK : >=3.4.0 <4.0.0
- Android Studio 
- A compatible device or emulator

## Installation

1. **Clone the repository:**

    `git clone [https://github.com/vijaysanthoshp/Pandas-Bear-Classification.git]`
    `cd clubproject`
    
   

3. **Install dependencies:**

    ` flutter pub get`
  
   
4. **Ensure you have the required assets:**

   - `assets/model.tflite` - The TensorFlow Lite model file.
   - `assets/labels.txt` - The labels file for the model.

5. **Run the app:**

   `flutter run`
   
   
## Dependencies

The following dependencies are used in this project:
- `flutter`: Flutter SDK
- `flutter_tflite`: For using TensorFlow Lite in Flutter
- `image_picker`: For selecting images from the camera or gallery
- `cupertino_icons`: For iOS style icons

## Project Structure
- lib/main.dart: The main file containing the UI and functionality for image classification.
- assets/: Directory containing the TensorFlow Lite model, labels file, and placeholder image.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [Flutter](https://flutter.dev/)
- [TensorFlow Lite](https://www.tensorflow.org/lite)
- [image_picker](https://pub.dev/packages/image_picker)
- [flutter_tflite](https://pub.dev/packages/flutter_tflite)

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.  

## Usage

1. **Launch the App**

   After installing the app on your device, launch it from your app drawer or home screen.

2. **Splash Screen**

   When you open the app, you'll be greeted by a splash screen with an animated gradient background and the app logo. This screen will appear briefly before transitioning to the main screen.

3. **Main Screen**

   The main screen features a container where you can either take a photo or select an image from your gallery for classification.

4. **Taking a Photo**

   To take a photo, tap the "Take Photo" button. This will open your device's camera app. Once you've captured an image, the app will analyze it and display the classification result.

5. **Selecting an Image from Gallery**

   If you prefer to use an existing image, tap the "Select from Gallery" button. This will open your device's file picker, allowing you to navigate to and select an image from your photo gallery. After selecting an image, the app will analyze it and show the classification result.

6. **Classification Result**

   After the image is analyzed, the app will display the classified label (e.g., "Panda" or "Bear") and the confidence level as a percentage. The higher the confidence level, the more accurate the classification is likely to be.

7. **Resetting the Image**

   If you want to clear the selected image and start over, tap the "Reset" button. This will remove the current image and reset the classification result.

8. **About Section**

   To learn more about the app and how it works, tap the "About" button. This will open a modal bottom sheet with information about the app's functionality and purpose.

9. **Exiting the App**

   To exit the app, simply follow your device's standard procedure for closing apps (e.g., pressing the back button or swiping the app away from the recent apps list).
   
## VIDEO

https://github.com/vijaysanthoshp/Pandas-Bear-Classification/assets/143861101/afb1f493-0daf-44a3-85b4-3d99ab22b9fc

## Contact
For any inquiries or issues, please contact [vijaysanthoshpandiyaraj@gmail.com].

