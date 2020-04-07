# DC-GAN to generate Simpsons like characters

The Simpsons Faces image dataset was downloaded from Kaggle and saved in Google Drive: https://www.kaggle.com/kostastokis/simpsons-faces

The images were resized to 64x64.

The models were trained using Google Colab Pro.

# Experiment 1
The baseline was the work presented by Greg Surma:
https://towardsdatascience.com/image-generator-drawing-cartoons-with-generative-adversarial-networks-45e814ca9b6b

The model was converted to Keras.

The Notebook is dcgan_simpsons_experiment1.ipynb.

This is the result when the model was trained with 100 epochs:

![Images during training](https://github.com/ravasconcelos/simpsons_dcgan/blob/master/dcgan_simpsons_experiment1.gif?raw=true)

# Experiment 2
The baseline was the TensorFlow Tutorial for DCGAN:
https://www.tensorflow.org/tutorials/generative/dcgan

The Notebook is dcgan_simpsons_experiment2.ipynb.

This is the result when the model was trained with 300 epochs:

![Images during training](https://github.com/ravasconcelos/simpsons_dcgan/blob/master/dcgan_simpsons_experiment2.gif?raw=true)

# Generated Simpsons characters
In this folder you can see some characters generated when the model in the experiment 2 was trained with 1000 epochs:
https://github.com/ravasconcelos/simpsons_dcgan/tree/master/generated_images

![Images during training](https://github.com/ravasconcelos/simpsons_dcgan/blob/master/generated_images/image01.png)
![Images during training](https://github.com/ravasconcelos/simpsons_dcgan/blob/master/generated_images/image02.png)
![Images during training](https://github.com/ravasconcelos/simpsons_dcgan/blob/master/generated_images/image03.png)
![Images during training](https://github.com/ravasconcelos/simpsons_dcgan/blob/master/generated_images/image04.png)
![Images during training](https://github.com/ravasconcelos/simpsons_dcgan/blob/master/generated_images/image05.png)
![Images during training](https://github.com/ravasconcelos/simpsons_dcgan/blob/master/generated_images/image06.png)
![Images during training](https://github.com/ravasconcelos/simpsons_dcgan/blob/master/generated_images/image07.png)
![Images during training](https://github.com/ravasconcelos/simpsons_dcgan/blob/master/generated_images/image08.png)
![Images during training](https://github.com/ravasconcelos/simpsons_dcgan/blob/master/generated_images/image09.png)
![Images during training](https://github.com/ravasconcelos/simpsons_dcgan/blob/master/generated_images/image10.png)
![Images during training](https://github.com/ravasconcelos/simpsons_dcgan/blob/master/generated_images/image11.png)
![Images during training](https://github.com/ravasconcelos/simpsons_dcgan/blob/master/generated_images/image12.png)
