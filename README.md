# Invisible-Cloak
🪄 Invisible Cloak using OpenCV

Step into the magical world of invisibility! Inspired by the iconic invisibility cloak from Harry Potter, this project makes you disappear in real-time using OpenCV and computer vision techniques. Just wear a specific colored cloak (like blue), and watch the magic happen on your screen! ✨

# 🚀 Features

~ Real-Time Invisibility: Make objects of a specific color vanish on live video.
~ Customizable Cloak Color: Easily change the cloak's color by tweaking HSV values.
~ Smooth and Efficient: Uses optimized image processing techniques for seamless performance
~ Dynamic Background Capture: Adjusts to the environment for better accuracy.

# 🛠️ Installation
1. Clone this repository:
```bash
  git clone https://github.com/yourusername/invisible-cloak.git
  cd invisible-cloak
```
2. Install the required packages:
   ```bash
     pip install opencv-python numpy
   ```
3. Run the program:
   ```bash
   python invisible_cloak.py
   ```

# 🧙‍♂️ How It Works

1. Background Capture: Captures multiple frames to create a median background image.
2. Color Detection: Uses HSV color space to detect the chosen cloak color.
3. Mask Creation: Generates a binary mask where the cloak is detected.
4. Image Blending: Combines the background and foreground to give the invisibility effect.

# 🎨 Customization

Change the cloak color by updating these values in the script:
```bash
  lower_blue = np.array([90, 50, 50])
  upper_blue = np.array([130, 255, 255])
```
Replace lower_blue and upper_blue with your desired HSV values.

# 📝 Usage Tips

~ Make sure your cloak has a distinct color that doesn’t blend with the background.
~ Ensure good lighting for accurate color detection.
~ Adjust the HSV range to fine-tune the invisibility effect.

# 🤝 Contributing

Got some cool ideas? Feel free to open an issue or submit a pull request. Let's make invisibility even cooler together! 😎

