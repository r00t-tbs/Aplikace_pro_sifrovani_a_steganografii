# Encryption and Steganography Application

## **Overview**
This WinForms project combines text encryption using the **Caesar Cipher** algorithm and steganography using the **LSB (Least Significant Bit)** technique to hide encrypted messages into images.

---

## **Workflow**

1. **Text Encryption**:
   - Input your message in the text field.
   - Select the **shift key** for Caesar Cipher.
   - Encrypt or decrypt the message with respective buttons.

2. **Steganography**:
   - Load an image (PNG or BMP) from your system.
   - Enter the text to hide and encrypt it.
   - Hide the text within the image using the LSB technique.
   - Save the new image containing the hidden message.

3. **Text Extraction and Decryption**:
   - Load the image with hidden text.
   - Extract the hidden message.
   - Decrypt the message using the Caesar Cipher key.

---

## **Features**
- **Caesar Cipher**: A simple encryption method based on shifting letters.
- **LSB Steganography**: Hides binary text data in the least significant pixel bits.
- **User-Friendly Interface**: Text input fields, buttons, and file dialogs.
- **ProgressBar**: Provides visual feedback during operations.

---

## **Legend**
- **Caesar Cipher**: A substitution cipher where each letter is shifted by a fixed number.
- **Shift Key**: A numeric value to determine the letter shift.
- **LSB Steganography**: Embeds data into the least significant bits of image pixels.
- **Bitmap**: A pixel-based image format suitable for steganography.
- **Encryption**: Converting plain text into unreadable ciphertext.
- **Decryption**: Reversing encryption to retrieve the original message.

---

## **Basic Cryptography Terms**
1. **Plaintext**: Original message before encryption.
2. **Ciphertext**: Encrypted message.
3. **Key**: A parameter for encryption/decryption.
4. **Steganography**: Concealing information within another medium.
5. **AES (Advanced Encryption Standard)**: A secure, symmetric encryption algorithm.

---

## **Running the Application**
1. Build and run the application in Visual Studio.
2. Use the buttons to perform encryption, hiding, and extraction tasks.
3. Ensure you have valid images for the steganography process.

---

## **Future Enhancements**
- Support for AES and RSA encryption algorithms.
- Visual representation of pixel changes during steganography.
- Support for hiding larger files into images.

---

## **Credits**
Developed by Anar Safiyev.
