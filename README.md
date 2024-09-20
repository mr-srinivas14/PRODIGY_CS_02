# Mr. Srinivas's Pixel Manipulation for Image Encryption Tool

## 1. Description
Mr. Srinivas's Pixel Manipulation for Image Encryption Tool is a Python-based image encryption and decryption tool. It performs simple pixel-level manipulation by inverting the RGB values of each pixel in an image to encrypt it. Decryption is achieved by reversing this process. This tool provides a user-friendly interface in the terminal, where users can easily encrypt and decrypt image files.

## 2. Features
- **Simple Pixel Manipulation**: Encrypt and decrypt images by inverting pixel values.
- **Command-line Interface**: Easy-to-use text-based interface to perform encryption and decryption.
- **Customizable Output**: Users can specify their own input and output file paths for encrypted and decrypted images.
- **Encryption and Decryption**: The same method used for encryption can be applied to decrypt the image back to its original form.

## 3. Getting Started
To get started with the Pixel Manipulation for Image Encryption Tool, follow the instructions below to install the necessary dependencies and run the tool.

### 4. Prerequisites
You will need to have Python installed on your system. Additionally, the following Python package is required:
- `Pillow` (for image processing)
You can install Pillow using `pip`:
```bash
pip install Pillow
```

## 5. How to Install
1. Clone or download this repository to your local machine.
```bash
https://github.com/mr-srinivas14/PRODIGY_CS_02.git
```
2. Ensure that `Pillow` is installed by running:
```bash
pip install Pillow
```
Make sure you have Python installed. Check by running:
```bash
python --version
```

## 6. How to Run
1. Open a terminal in the project directory.
2. Run the tool by executing the following command:
```bash
python Pixel_Manipulation_For_Image_Encryption.py
```
3. Follow the on-screen prompts to encrypt or decrypt images.

## 7. Usage Example
**Example of encrypting an image:**
- When the program starts, choose the option to encrypt an image by typing ```E.```
- Provide the path to the image you want to encrypt, for example: ```input_image.jpg.```
- Specify the output path for the encrypted image, such as ```encrypted_image.jpg.```
- The image will be processed, and an encrypted version will be saved to the specified location.

**Example of decrypting an image:**
- Choose the option to decrypt an image by typing ```D.```
- Provide the path to the encrypted image, for example: ```encrypted_image.jpg.```
- Specify the output path for the decrypted image, such as ```decrypted_image.jpg.```
- The image will be decrypted and saved to the specified location.

## 8 . Sample Interaction

 ___  _ __   __ ___  _     __ __   __   __  _  _  ___  _  _  _     __  _____  _   __   __  _  
| _,\| |\ \_/ /| __|| |   |  V  | /  \ |  \| || || _,\| || || |   /  \|_   _|| | /__\ |  \| | 
| v_/| | > , < | _| | |_  | \_/ || /\ || | ' || || v_/| \/ || |_ | /\ | | |  | || \/ || | ' | 
|_|  |_|/_/ \_\|___||___| |_| |_||_||_||_|\__||_||_|   \__/ |___||_||_| |_|  |_| \__/ |_|\__| 
===============================================================================================
- Welcome to Mr Srinivas's Image Encryption Tool
- What do you want to Do:
- Type E To Encrypt an image
- Type D To Decrypt an image
- Type C To cancel and Exit the Program
- Please Type your choice (E or D): E

Enter the path of the image file: input_image.jpg
Enter the output path for the encrypted image: encrypted_image.jpg
Image encrypted and saved as encrypted_image.jpg


**Credits:** : Developed By ```Mr Srinivas```
