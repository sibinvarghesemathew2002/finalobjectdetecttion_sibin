


# Steps for running the project

## 1. Create a new virtual environment, as example "myenv10", and paste all the files in this environment.
      python -m venv myenv10


## 2. Change the directory path to "myenv10" 
      cd myenv10

## 3. Activate the Scripts File
      Scripts\activate

## 4. Virtual environment gets activated by the above command.

## 5. Installation of necessary packages is mandatory.

      pip install --upgrade pip
      pip install opencv-python
      pip install ultralytics
      pip install torch torchvision torchaudio --index-url 
      pip install labelImg


## 6. The file named as "main.py" is the main file which includes the python script for calculationg object dimension

## 7. The test images are mentioned as " test49", "test50", "test51", "test52","test53", test54", "test55".

## 8. Run the command using this syntax "python main.py -i <path_to_image> -w <width_of_known_object>"

## 9. For example if i want to test the image "test49". Please note to change the path accordingly. 
      python main.py -i "D:\ObjectDimension\Calculation-of-Object-Dimensions\myenv10\test49.jpg" -w 2

## 10. Likewise we chan check for different test images by changing the test images file name.

## 11. As output, now the objects in the image, will be displayed along with appropriate dimensions( height and width) in centimeters.





