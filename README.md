### 🛡️ Steganography Tool - Hide Messages in Images

This is a simple Python script for **steganography**, allowing users to hide and retrieve secret messages inside an image using OpenCV.

# 🚀 Features
- Encrypts a text message inside an image.
- Uses pixel manipulation to encode characters.
- Requires a passcode for decryption.
- Saves the encrypted image as `encryptedImage.jpg`.

## 🛠️ Installation & Requirements
Ensure you have **Python 3.x** installed along with the required dependencies:

```
pip install opencv-python
```

## 📌 Usage

### 🔐 Encryption
1. Place your image in the project directory (default: `cyber.jpg`).
2. Run the script:

   ```
   python stego.py
   ```

3. Enter the **secret message** and a **passcode** when prompted.
4. The modified image will be saved as `encryptedImage.jpg`.

### 🔓 Decryption
1. Run the script again:

   ```
   python stego.py
   ```

2. Enter the **same passcode** used during encryption.
3. If the passcode matches, the hidden message will be displayed.

### ⚠️ Notes
- The script modifies pixel values directly to store characters.
- Only **ASCII characters** (0-255) can be encoded.
- Ensure the **same image** is used for encoding and decoding.

### 🏗️ Future Improvements
- Implement better **encryption methods** for higher security.
- Support for **larger text messages**.
- Improve storage technique to avoid noticeable image distortion.

---
