# tensorflow_model_optimization

This repository is part of my YouTube video on Quantization in TensorFlow (Link: https://youtu.be/JdRYjWWpXAs )

This repository contains two files: quantization_aware_training.ipynb and post_training_integer_quant.ipynb

quantization_aware_training.ipynb provides you with a tutorial to explore Quantization Aware Training in TensorFlow.

In this tutorial you will:
1. Train a tf.keras model for MNIST from scratch.
2. Fine tune the model by applying the quantization aware training API, see the accuracy, and export a quantization aware model.
3. Use the model to create an actually quantized model for the TFLite backend.
4. See the persistence of accuracy in TFLite and a 4x smaller model.


post_training_integer_quant.ipynb provides you with a tutorial to explore Post-Training Integer Quantization in TensorFlow.

In this tutorial, you'll
1. train an MNIST model,
2. convert it into a Tensorflow Lite file,
3. and quantize it using post-training quantization. 
4. Finally, you'll check the accuracy of the converted model and
5. compare it to the original float model.
