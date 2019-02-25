# glow-pytorch

PyTorch implementation of Glow, Generative Flow with Invertible 1x1 Convolutions (https://arxiv.org/abs/1807.03039)

Usage:

> python train.py PATH

as trainer uses ImageFolder of torchvision, input directory should be structured like this even when there are only 1 classes. (Currently this implementation does not incorporate class classification loss.)

> PATH/class1 <br/>
> PATH/class2 <br/>
> ...

## Notes

![Sample](sample.png)

![Progression of samples](progression.gif)

## code

https://github.com/rosinality/glow-pytorch

## Demo

https://blog.openai.com/glow/

### Code
https://github.com/openai/glow

## Models

https://github.com/modulabs/Deep-Generative-Models/blob/master/1st/7.%20Flow-based%20Models%20-%20Practice/glow-pytorch/models.txt
