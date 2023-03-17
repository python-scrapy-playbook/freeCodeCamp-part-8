# Installation Guide
If you want to get started with part 8 of the FreeCodeCamp Python Scrapy course. Follow the steps below.

The link to the part 8 article: 
https://thepythonscrapyplaybook.com/freecodecamp-beginner-course/freecodecamp-scrapy-beginners-course-part-8-fake-headers-user-agents/


## Step 1 - Install & activate your python virtual environment
To install the python virtual environment follow the following instructions below.

For Mac: https://thepythonscrapyplaybook.com/freecodecamp-beginner-course/freecodecamp-scrapy-beginners-course-part-2-scrapy-environment/#setting-up-your-python-virtual-environment-on-macos

For Windows: https://thepythonscrapyplaybook.com/freecodecamp-beginner-course/freecodecamp-scrapy-beginners-course-part-2-scrapy-environment/#setting-up-your-python-virtual-environment-on-windows 

For Linux: https://thepythonscrapyplaybook.com/freecodecamp-beginner-course/freecodecamp-scrapy-beginners-course-part-2-scrapy-environment/#setting-up-your-python-virtual-environment-on-linux

Then to activate it so that any new modules that are installed are installed into this virtual environment:

`source venv/bin/activate`



## Step 2 - Install the required python modules
To install the required modules for this python project to run you need to install the required python modules using the following command:

`pip install -r requirements.txt`


## Step 3 - Run the project/ Follow the course
Once the required python modules are installed you should be able to view/run the Python Scrapy Spider with the following command (from within the project folder):

Cd into the project spiders: `cd bookscraper`

View the project spiders: `scrapy list`

Run the project spider: `scrapy crawl bookspider`



# Helpful Dubugging 
If you have issues running the `pip install -r requirements.txt` command this can be due to some things not being up to date on your computer. 

Running the following may solve some of these issues:

`pip install --upgrade pip`

The following error: `NotADirectoryError: [Errno 20] Not a directory: 'pkg-config'` might be solvable by running:
`export PKG_CONFIG=/path/to/pkg-config`