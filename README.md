# trying-out-YOLO


Trying out YOLO for real-time object detection

https://pjreddie.com/darknet/yolo/

```Successful Classification of .JPEG Image```

<img width="603" alt="Screenshot 2023-02-14 at 4 19 19 PM" src="https://user-images.githubusercontent.com/95064358/218764889-e59402b3-ce3a-4dd1-8603-d515059f1ab7.png">

![predictions](https://user-images.githubusercontent.com/95064358/218765412-4308d050-5c11-4db5-9180-5ee629a3606a.jpg)

```Multiple Images```

![predictions](https://user-images.githubusercontent.com/95064358/218766369-aff8e979-5a17-4e1a-9998-fc073d21b7f5.jpg)

```Tiny YOLO```

There were fewer layers in this case, and the prediction took significantly less time.

<img width="600" alt="Screenshot 2023-02-14 at 4 35 57 PM" src="https://user-images.githubusercontent.com/95064358/218769496-32a7cad9-316c-43b4-8404-038a9c936b66.png">

![predictions](https://user-images.githubusercontent.com/95064358/218769592-ec4c7146-0221-4bb4-a1da-f3d643e89d02.jpg)

```Open Images dataset```

<img width="607" alt="Screenshot 2023-02-14 at 5 03 19 PM" src="https://user-images.githubusercontent.com/95064358/218776184-b14369d0-2b59-42bc-8935-e3f6657ed2a6.png">

![predictions](https://user-images.githubusercontent.com/95064358/218776229-1d21e26b-b200-4710-953e-23d3656e6a64.jpg)

We could also use the Open Images dataset. In this case, the predictions were less precise and took longer to complete.

```Training YOLO on COCO```

<img width="374" alt="Screenshot 2023-02-21 at 9 24 44 PM" src="https://user-images.githubusercontent.com/95064358/220439620-270da083-c8f0-4d1c-895e-4436b239e712.png">

I have also set up the necessay requirements to train YOLO on COCO on my local machine. Unfortunately it takes too long to train on a MacBook. Nonetheless, it was a good exercise.

```Reflections```

Overall, it was interesting to try out the different functionalities of YOLO and try to train the model on my local machine. Through the process, I also got a better understanding of the trade-off between computational efficiency and accuracy. 

I have also began reading the paper published by Joseph Redmon to learn more about the theoretical foundation of YOLO. The pdf can be found in this repository.




