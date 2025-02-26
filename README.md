# Stegnography-IBM
Project for IBM Edunet Skillsbuild Internship Program

# Steganography

This project is a part of the IBM skillsbuild internship program.

## Steganography using Least Significant Bit (LSB) Method

### Overview
This project implements a simple image steganography technique using the Least Significant Bit (LSB) method. It allows users to hide a secret message inside an image and retrieve it later using OpenCV.

### Features
- Encode a secret message into an image
- Password-protected message embedding
- Retrieve and decrypt the hidden message
- Uses OpenCV for image processing

### Requirements
- Python 3.x
- OpenCV (cv2)

### Installation
Clone this repository:
bash
git clone https://github.com/yourusername/steganography-lsb.git
cd steganography-lsb

#### Steganography

This project is a part of the IBM skillsbuild internship program.

## Steganography using Least Significant Bit (LSB) Method

### Overview
This project implements a simple image steganography technique using the Least Significant Bit (LSB) method. It allows users to hide a secret message inside an image and retrieve it later using OpenCV.

### Features
- Encode a secret message into an image
- Password-protected message embedding
- Retrieve and decrypt the hidden message
- Uses OpenCV for image processing

### Requirements
- Python 3.x
- OpenCV (cv2)

### Installation
Clone this repository:
bash
git clone https://github.com/yourusername/steganography-lsb.git
cd steganography-lsb

## Usage

### Encoding a Message
1. Place the cover image in the project directory and rename it to `example.jpg`.
2. Run the script and choose encoding mode:
    ```bash
    python steganography.py
    ```
3. Enter the secret message and a passcode.
4. The encoded image will be saved as `encoded_example.png`.

### Decoding a Message
1. Run the script and choose decoding mode:
    ```bash
    python steganography.py
    ```
2. Enter the correct passcode.
3. Provide the length of the hidden message.
4. The message will be displayed.
