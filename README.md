# Chess-game
## Overview
This is a code to design chess game.
## Description
The code uses machine learning algorithm trained on previous played chess game between chess champions(like José Raúl Capablanca and Alexander Alekhine) and minimax algorithm.
1. Firstly you need to train your model using dataset(in my case i'm using https://github.com/richahere/chess_data dataset).
2. In order to do that, here is the code-https://colab.research.google.com/drive/1h3ITJyY7Ojb0lZHbx4szaVrK1cvgeLh8#scrollTo=8ydsOqd3LtnO
3. Now it's time to implement this model in our chess game. In order to do this save model that is obtained from training part(https://github.com/richahere/chess) and using this model do the coding(https://colab.research.google.com/drive/1rxp5h6wBwYui7pDEHW-h-oBGbqBgFOES#scrollTo=cgYlwFkVulJI) 
## Dependencies
1. python 3
## Run
1.Training Part-
    -import these libraries (glob, os, tensorflow, pandas, numpy, sklearn).
    -Now mount your gdrive(to store the trained model)
    -I am importing dataset from my github. So here i am clonning my github.
    -Use TensorFlow library to train the dataset.
    -Press ctr+A button to run code(https://colab.research.google.com/drive/1h3ITJyY7Ojb0lZHbx4szaVrK1cvgeLh8#scrollTo=8ydsOqd3LtnO)
    -Save model.
2.Chess game 
     -import these libraries (chess, chess.svg, cairosvg, collections import OrderedDict, operator import itemgetter, pandas, numpy, tensorflow, IPython.display import clear_output, cv2, google.colab.patches import cv2_imshow.
     -In order to import the model i am clonning github.
     -Press CTRL+A to run the code(https://colab.research.google.com/drive/1rxp5h6wBwYui7pDEHW-h-oBGbqBgFOES#scrollTo=cgYlwFkVulJI).
     -In order to play press valid key(refer to this image)
                                    ![image](https://user-images.githubusercontent.com/91825767/172993233-61d7f70b-1ae4-461f-9714-86a49dab768d.png)
                                     Suppose you want to move piece at e2 to e3. Press(e2e3).
   ## Reference
   -https://www.kaggle.com/search?q=chess+dataset
   -https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/
   -https://www.youtube.com/watch?v=bJfqn4Ysvsk&ab_channel=NextDayVideo
   -https://python-chess.readthedocs.io/en/latest/
     
