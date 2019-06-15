# Final Project

Jaka Bauer, jjbauer@ucsd.edu

## Abstract Proposal

For my final project, I'll revisit my generative sketch project. I was dissappointed in this project, as I felt it failed my artistic concept even though I spent a large amount of time on collecting the data. In revisiting this project, I'm first going to get the code to successfully generate the river sketches I wanted to acheive in the original. Then, I'll move on to modifying the generation code to "predict" a river sketch given an incomplete sketch. I plan on referencing the way the sketchRNN examples predict user input to generate an array of possible sketches. As my "user input" I will draw vector drawings of rivers I'm interested in. Ideally if i have time I would use edge detection to fully automate this vector drawing proccess so I could just input the satellite image of the river I'm interested in--but I feel that is too ambitious of a plan considering the limited amount of time I have. As far as presenting, I will introduce the work of Carolina Caycedo as the inspiration for my project, especially my interest in Caycedo's use of scale, inversion, and imagination and how I adapted that in my own rendition. To polish the product from an artistic standpoint, I will print the satellite images I used to generate the rivers and paint with ink on top of the path that my RNN sketches for me (I'll be using materials that I already have from taking a calligraphy course). I really enjoy the tactileness of creating art with my own hands, and I don't want to completely disconnect art from the human. In this way I want my RNN to be more of a companion to help me imagine my sketches--since in theory it should have a more nuanced understanding of the flow/shape of a river.

## Project Report
See ECE Final Project Report.pdf above.

## Model/Data
I used the sketch rnn model to train my data. My data is originally from NaturalEarthData.com, but has been extremely processed to fit the needs of this project:
Data: low_cov_river_samples.npz
Model Parameters/Logs: logs.zip

## Code

- Colab notebook: Generating_Rivers_Sketch_RNN.ipynb

## Results
Typical results can be seen in files ouput1.png - output5.png
A stylized hand-rendered result is seen on cover of report.

## Technical Notes

- Uses Colab, so you have to upload files to Drive and mount drive to Colab environment to get this to work. Also note that youre path names will be different than mine so you must change them to match your file locations in your drive in the code.

## Reference

An image of my inspiration for this project is Caycedo.png
