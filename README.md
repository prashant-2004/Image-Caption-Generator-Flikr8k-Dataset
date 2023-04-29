# Image-Caption-Generator-Flikr8k-Dataset
Model for generating the Caption for the Image based on the flikr8k dataset for training

This model is a deep learning model which uses the tensorflow and keras libraries which are used for Neural Network.

It trains on the basis of the name of image and its corresponding nearly 5 captions related on that image. 
The dataset for this is Flikr8k which is available on - https://www.kaggle.com/datasets/adityajn105/flickr8k?resource=download

To run the our model successfully..,we need to follow some steps explained below - 

1. Download the kaggle dataset from above given link which is the most important step.
2. You need to ready with jupyter lab - if you don't have it, then type following command on Command Promt for installing of jupyter Lab - 
         
         pip install jupyterlab
3. Then, Install the tensorflow library using Command Promt to train & develp an Model - 

        pip install tensorflow     
4. Install tqdm library using Command Promt which giving us UI to see how many data is processed till now - 

        pip install tqdm
5. Install NLTK(Natural Language Toolkit) library using Command Promt which gives us an accuracy score using bleu_score - 

        pip install NLTK
6. Install pillow library using Command Promt which is used to load the image and applying other processing on the image -
  
        pip install pillow
7. Install pydot library using Command Promt which is used to plot the Model - 

        pip install pydot
8. For plotting model – 
        a.	In windows, we need to download the graphviz software (In this repository, in software folder, I had provided with a GraphViz               Software Installer for Windows-x64) from https://graphviz.gitlab.io/download/
        b.	After Installation done, copy bin folder path like, C:\Program Files\Graphviz\bin
        c.	ADD this path to the Environmental variables in user section.

9. Lastly, copy the whole repository folder in the " C:/user/your-name "(C-Drive) i.e., where windows is exists
10. After all installation process over, type the <jupyter-lab> command on Command Promt
11. Then, open this repository folder in the Jupyter and in that open "Image_Caption_Generator.ipynb" file and run this file one by one.
12. AND, FINALLY YOUR MODEL GIVES YOU AN CAPTIONS accordingly the file name providing by CHANGING FILE NAME(get file-names from captions.txt file) in the last Line of code.   
  
NOTE: - It takes more time for extracting the features, training the model, and while getting BLEU_Score as it has 90% of 8k images for training. 
