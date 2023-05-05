This repository provides a web interface to detect scratches in sensor images using UNET.

Install the requirements using following command:
pip install -r requirements.txt

The steps to run the web interface can be found below:

Clone this repository or download the zip file.

Cd to the extracted zip folder or downloaded git repository.

Run the command flask run. flask run

Go to the website http://127.0.0.1:5000 on your local web browser. You will be directed toward the web interface.

Select the files and upload them using Upload Button.

After clicking the Upload Button, the images will be stored in instance/upload/ with the current date and time folder. The Yolo model will be implemented on the images and the result annotated images will be stored on /static/ folder with the current date and time folder. The annotated images will be displayed on the web interface.

The resulting image labels can be downloaded with the "Download Label Files" Button. The downloaded file will be in the form of zip.

You can filter the images with the drop-down button.
