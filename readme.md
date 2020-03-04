# Don't touch your face

[live demo](https://mirceanis.github.io/stopncov19/index.html)

I made a toy to detect when I'm touching my face (unconsciously) and make some noise to let me know.
This should reduce transmission of germs if my hands get contaminated.

It uses the laptop camera and pipes it to a ML model with tensorflow JS, and shows the predicted probability of the 2 classes ("Touching" "Not touching").

The model is trained on my face so I'm not sure how it will behave when you use it.

### Use your own model

Train your own image model on https://teachablemachine.withgoogle.com/ and download the tensorflow.js variant.
Unzip it and replace the files in [docs/my_model](docs/my_model)
 

### Credits

This was built using code from https://teachablemachine.withgoogle.com/

The punch sound comes from https://freesound.org/s/507131/