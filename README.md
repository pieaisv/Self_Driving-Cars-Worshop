
Implementation of the paper "End to End Learning for Self-Driving Cars"

## Citing

If you find this code useful in your research, please consider citing the blog:




## Goal

Train a end-to-end deep learning model that would let a car drive itself around the track in a driving simulator.

## Data collection

In this project Udacity driving simulator has been used which has two different tracks. One of them was used for collecting training data, and the other one — never seen by the model — as a substitute for test set.

The driving simulator would save frames from three front-facing "cameras", recording data from the car's point of view; as well as various driving statistics like throttle, speed and steering angle. We are going to use camera data as model input and expect it to predict the steering angle in the [-1, 1] range.

## Results

<p align="center">
  <img src="run.gif" alt="Driving"/>
</p>


Video: https://www.youtube.com/watch?v=hTPADovdyfA&t=99s
## References

1. https://arxiv.org/pdf/1604.07316.pdf

2. http://cs231n.stanford.edu/reports/2017/pdfs/626.pdf

