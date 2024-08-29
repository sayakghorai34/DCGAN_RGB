Implementation of DCGAN from the paper "Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks" by Radford et al. (2016). https://arxiv.org/abs/1511.06434v2
The result is pleasing

![dcgan](https://github.com/user-attachments/assets/8836ea1f-ae10-47cb-9d88-897a1ca4dff9)


## Notes:
I have taken the template of the code from the tensorflow documentation, then trid to convert the logic into pytorch using pytorch documentation and chatgpt.
first of all, the model was not giving any meaningful results until I introduced the manual seeding. That helps to recreate the results.
But as the generated image starts from a randomly generated noise, every time the training will be different even with the same hyperparameters.
After trying to train 4-5 times with the same hyper-parameters, i have got these significantly good images
