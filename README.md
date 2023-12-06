# 👨‍💻 CAMOPIXER - An Image Steganographic Tool 🖥

A Java application that conceals messages within images, ensuring both security and functionality. 

>> Comprises several key components represented by individual files 📃

<img src= "https://github.com/prakash2903/CamoPixer/blob/main/CamoPixer/pictures/splash.png" height = 300, width = 425, align=left>

<img src= "https://github.com/prakash2903/CamoPixer/blob/main/CamoPixer/pictures/main.png" height = 300, width = 425>

## Steganographic Algorithm:

<img src= "https://miro.medium.com/v2/resize:fit:1400/1*Gu_RomzVTPMEJ1hfKanRBA.png" height = 200, width = 725>

* **The Least Significant Bit (LSB) image steganography algorithm**, a method for hiding
information within digital images. 

* Using this technique, each pixel&#39;s color values (typically red, green, and blue channels in RGB images) are altered by 
replacing the least significant bits with the secret message bits. 

* The secret message is divided into binary form, and each bit is inserted into the corresponding
pixel's LSB

* When the image is transmitted or shared, the recipient can extract the hidden message by examining the LSB of the pixels.

## 🔐 Encoder and Decoder 🖊

<img src= "https://github.com/prakash2903/CamoPixer/blob/main/CamoPixer/pictures/encode.png" height = 300, width = 425, align=left>

<img src= "https://github.com/prakash2903/CamoPixer/blob/main/CamoPixer/pictures/decode.png" height = 300, width = 425>



# ✅ How to RUN ?

IDE: Apache NetBeans IDE 18 

1. Download the repo as .zip

2. Extract the folders and open with IDE

3. Source packages >> default package >> main.java

4. Run main.java
   
