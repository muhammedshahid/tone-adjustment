# Tone Adjustment Using Otsu's Threshold in JavaScript

This project adjusts the tone of an input image using **Otsu's threshold adjustment**. The algorithm calculates the difference between the grayscale threshold and individual RGB channel thresholds, applying the result to enhance the tonal balance of the image.

## Key Features
- **Image Upload**: Users can upload images for tone adjustment.
- **Otsu's Threshold Calculation**: 
  - Computes the Otsu threshold for the grayscale image.
  - Determines individual Otsu thresholds for each RGB channel.
- **Tone Adjustment**: Adjusts the RGB channels based on the variation between the grayscale and RGB thresholds.
- **Enhanced Output**: Provides a tone-adjusted image for improved visual appeal.

## How It Works
1. **Input**: Users upload an image.
2. **Grayscale Threshold**: Otsu's threshold is calculated for the grayscale image.
3. **RGB Thresholds**: Otsu's thresholds are calculated for each RGB channel.
4. **Threshold Variation**: The grayscale threshold is subtracted from each RGB threshold to determine the variation.
5. **Tone Adjustment**: The variation is applied to the original image's RGB channels to adjust the tone.
6. **Output**: The tone-adjusted image is displayed alongside the original for comparison.

## Technologies Used
- **JavaScript**: Implements Otsu's threshold adjustment and tone correction algorithm.
- **Canvas API**: For rendering and manipulating the image data.

## How to Use
- Clone the repository:
   ```bash
   git clone https://github.com/muhammedshahid/tone-adjustment.git
- Open index.html in a browser.
- Upload an image using the upload button.
- View the tone-adjusted image and compare it to the original.
## Future Improvements
- Add real-time sliders to fine-tune tone adjustments.
- Support for tone adjustment presets (e.g., warm, cool tones).
- Option to save the tone-adjusted image locally.
## Contributing
- Contributions are welcome! Feel free to submit issues or pull requests to improve the project.
