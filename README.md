# Index Investing vs Active Investing

The goal of this project is to create a computer algorithm to manage an active investing portfolio (based on stock picking and market timing), and compare its returns against those of the S&P 500 index, from 2009 to 2022.

Please, keep in mind I am not considering any fees or taxes that may be applicable in real life, since there is too much variation depending on where you live and what services you use. 

And also please remember there is NO investment advice or financial advice 
of any kind here. This is only educational content. I am NOT a financial advisor, and I take 
NO responsibility over the consequences of any investing decision you take.

Some information in case you want to run this program locally: <br>
I ran this program on the Jupyter Notebook IDE, in a separate virtual environment created 
with virtualenv version 20.16.6, Python version 3.10.8, and pip version 22.3. 
The other required packages for running this program are in the `requirements.txt` file. 
If you clone this repository locally, you can run the code without changing anything, 
since you will have the all the data saved to your disk (~ 32.7 MB). If you don't want that, 
you will have to uncomment some code cells and comment others (as indicated in the notebook itself),
to download the data directly from the sources, and to avoid errors trying to read non-existing 
files. And in that case you would also need to manually download and place in the correct directory 
the `sp500change - sp500change.csv` file (the source is linked in the notebook).
