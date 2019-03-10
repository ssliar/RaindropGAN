# RaindropGAN
# Raindrop-RealTime
Pytorch implemation a real time raindrop model based on GAN.A extremely lightly model to make video real time raindrop.

**Prerequisites:**
- pytorch 3.6
- pytorch 0.4.1
- ubuntu 16.04

**Test on Image**
```
python test_image.py --input input_image --output output_image
```
**Test on Video**
```
python test_video.py --input video.mp4
```
**Results**
![1_input](imgs/1_input.jpg?raw=true "1_input")

![1_output](imgs/1_output.jpg?raw=true "1_output") 

![1_detect](imgs/1_detect.jpg?raw=true "1_detect") 

![2_input](imgs/2_input.jpg?raw=true "2_input") 

![2_output](imgs/2_output.jpg?raw=true "2_output")

![2_detect](imgs/2_detect.jpg?raw=true "2_detect") 

![3_input](imgs/3_input.jpg?raw=true "3_input") 

![3_input](imgs/3_output.jpg?raw=true "3_output") 

![3_input](imgs/3_detect.jpg?raw=true "3_detect") 

![4_input](imgs/4_input.jpg?raw=true "4_input") 

![4_input](imgs/4_output.jpg?raw=true "4_output") 

![4_input](imgs/4_detect.jpg?raw=true "4_detect") 

![5_input](imgs/5_input.jpg?raw=true "5_input") 

![5_input](imgs/5_output.jpg?raw=true "5_output")

![5_input](imgs/5_detect.jpg?raw=true "5_detect") 

**References**
- [**Non-locally Enhanced Encoder-Decoder Network for Single Image De-raining**](https://arxiv.org/abs/1808.01491).
  Guanbin Li, Xiang He, Wei Zhang, Huiyou Chang, Le Dong, Liang Lin.
- [Generative Adversarial Networks](https://arxiv.org/abs/1406.2661).
  Ian J. Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, 
  Sherjil Ozair, Aaron Courville, Yoshua Bengio.
- [YOLOv3:An Incremental Improvement](https://pjreddie.com/media/files/papers/YOLOv3.pdf).
  Joseph Redmon, Ali Farhadi.
