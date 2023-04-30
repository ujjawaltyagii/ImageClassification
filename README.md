# ImageClassification
(Trying my hands on Deep Learning)

- Build an "Image Classifier" using `Python`, `Tensorflow` and `Keras`.

- I have created this Image classifier in a `virtual environment` which is a good and ideal practice while working on these kind of projects as we import lots of libraries
and dependies so we don't want those files to mess up with other projects.

- I have used command : `!pip install tensorflow==2.8 tensorflow-gpu==2.8 opencv-python matplotlib  protobuf==3.19.1` instead of
`!pip install tensorflow tensorflow-gpu opencv-python matplotlib` as 
<b>Tensorflow has dropped native windows support for GPU usage in their latest versions of tensorflow</b>

- 1 and 0 labels done by the dataset API relate itself to the 0 and 1 determined by the model's sigmoid function <b>(0 - Happy , 1 - Sad)</b>.

- Got a handful experience on using `cuDNN` and `CUDA`, 
In particular the versions I have used are given below : - 

![image](https://user-images.githubusercontent.com/115401171/235368261-0cb118a2-654a-44a1-9922-d153f9a2f705.png)
![image](https://user-images.githubusercontent.com/115401171/235368276-4eca94d1-94d8-4efa-9ec9-789411be823c.png)

- `CUDA`, `cuDNN` and `MSVC` version should be carefully selected according to the tensorflow verstion in you system otherwise It wont work properly !
### Why GPU ?

- We use `tensorflow-gpu` instead of simple `tensorflow` to reduce the time taken by model in training as we generally have a large dataset so It takes a lot of time 
that's where GPU helps in making process a lot faster. <br>
(You can use `!pip install tensorflow tensorflow-gpu opencv-python matplotlib` for tensorflow without GPU)

- Can we run without GPU ? Answer is <b>YES !</b>

