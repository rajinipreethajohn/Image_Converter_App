# Image Converter App

This is a simple image converter app that allows you to convert your favorite photo to different effects such as a pencil sketch, a grayscale image, or an image with a blurring effect.

## Prerequisites

Make sure you have the following libraries and packages installed:

- Streamlit
- NumPy
- OpenCV (cv2)
- Pillow (PIL)

You can install them using the following command:

```
pip install streamlit numpy opencv-python pillow
```

## Usage

1. Clone the repository or download the project files.

2. Open the terminal or command prompt and navigate to the project directory.

3. Run the following command to start the app:

   ```
   streamlit run app.py
   ```

4. The app will open in your web browser.

5. Upload your photo by clicking the "Browse files" button.
   ![graph](/images/img1.png)
6. The app will display the "Before" and "After" images side by side.
    

7. Select the desired conversion option from the sidebar:

   - Original: Displays the original image without any conversion.
   ![graph](/images/img2.png)
   - Gray Image: Converts the image to grayscale.
   ![graph](/images/img3.png)
   - Black & White: Converts the image to black and white with adjustable intensity.
   ![graph](/images/img4.png)
   - Pencil Sketch: Converts the image to a pencil sketch with adjustable intensity.
   ![graph](/images/img5.png)
   - Blurred Effect: Applies a blurring effect to the image with adjustable intensity.
   ![graph](/images/img6.png)

8. Adjust the intensity sliders (if desired) to control the effect.

9. The "After" image will update automatically based on your selection.

10. Explore different conversion options and download the modified image if desired.

## About the App

This app provides a user-friendly interface to easily convert images to various effects. It uses the Streamlit framework for the web interface and libraries like NumPy, OpenCV, and Pillow for image processing. The sidebar contains a brief description of the app, and the main section allows users to upload images and apply different conversions. The app supports file formats such as JPG, PNG, and JPEG.

Feel free to customize and enhance the app according to your requirements. Enjoy converting your images with different effects!

**Note**: The app currently supports grayscale conversion, black and white conversion, pencil sketch effect, and blurring effect. You can extend the app to include additional conversion options or enhance the existing functionalities as needed.
