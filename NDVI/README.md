# NDVI calculation script
    This script use NGB (Nir, Green, Blue) Raspberry Pi NoIR image


##### First you need to do:
######    1. If you wish to use virtualenv.
Description | Command
------------ | -------------
1.1 install virtualenv by executing in console | "pip install virtualenv"
1.2 Go to the folder where you whant to have virtual env | cd my_project_folder
1.3 Create virtualenv by | virtualenv <name of you virtual environment>
1.4 Activate virtualenv | source /<path_to_virtual_env>/<name of you virtual environment>/bin/activate
###### 2. Install requirements.txt.
Description | Command
------------ | -------------
2.1 Go to you project folder | cd <path to project>
2.2 Execute | pip install -r requirements.txt

## Script usage NDVI.py
   Keys:
   >
   * -i, input image
   * -o, output path and file name by default it use 'NDVI.jpg'
   * -c, colors to create colormap by default it use -- 'gray', 'gray', 'red', 'yellow', 'green'


Examples:
>
 __>>> **python NDVI.py -i image.jpg -o test.jpg**__ <br />
 __>>> **python NDVI.py -i image.jpg -o test.jpg -c red green blue**__ <br />
 __>>> **python NDVI.py -i image.jpg**__ <br />
