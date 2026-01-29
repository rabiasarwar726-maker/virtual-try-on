 
# **Virtual Try-On System (Image-Based)**

## **Description**
The Virtual Try-On System allows users to upload a person image and a transparent garment PNG to visualize how the garment looks on the body. The system uses pose detection to automatically position shirts or pants using a simple 2D image overlay approach.

## **Features**
- Upload person and garment images (front-facing)  
- Automatic garment positioning using pose landmarks  
- Supports transparent PNG shirts and pants  
- Fit status detection (Good / Tight / Loose)  
- Simple Streamlit-based interface  

## **Tech Stack **
- Python 3  
- Streamlit  
- OpenCV  
- MediaPipe  
- Pillow  
- NumPy  

## **How to Run **

git clone https://github.com/rabiasarwar726-maker/virtual-try-on.git
cd virtual-try-on
pip install -r requirements.txt
streamlit run app.py


Notes :

- Garments must be transparent PNGs
- Only front-facing images are supported
- This is a 2D virtual try-on system (no cloth physics)

Screenshot
 <img width="1024" height="1536" alt="resul1" src="https://github.com/user-attachments/assets/880d5e4e-44ab-4b9d-8f84-6b6a9fe85f6f" />
 <img width="1024" height="1536" alt="result 2" src="https://github.com/user-attachments/assets/fb02a95b-1439-4c51-8600-a3b3d129c955" />
 <img width="1024" height="1536" alt="result3" src="https://github.com/user-attachments/assets/beb1cc7b-e5b0-464f-b6a1-532743768123" />
 <img width="1024" height="1536" alt="result4" src="https://github.com/user-attachments/assets/2bf58c66-44ca-4c69-a596-6ef131712601" />







## **Purpose** :

This project is developed for educational and academic purposes, focusing on pose detection and image-based virtual try-on using computer vision techniques.
Author: 
           Rabia Sarwar





