# Tostel
3D jump game based on Unity

Unity version 1010.1.10

# Main Idea
<img width="867" alt="Main image" src="https://github.com/sanho-is-coral/Tostel/assets/77918183/c85efccb-5a36-4cf6-839d-99b76b12144f">

The goal of the game is to move the character to the top using arrow buttons.

A left or right drawer of the next level randomly opens when the character reaches a certain level.

The door opens with a playing sound irregularly controlled by random factors.

If the character moves in the wrong direction or when the door is opened, the game plays game over scene.

# Game Scene
Start scene

![startscene-ezgif com-video-to-gif-converter](https://github.com/sanho-is-coral/Tostel/assets/77918183/b3e7f9e5-cae1-49d7-a92b-d0713233de2e)

How the game works

![dead](https://github.com/sanho-is-coral/Tostel/assets/77918183/e189cf32-b81d-4033-9a96-c26610ccdf25)

Success ending

![success](https://github.com/sanho-is-coral/Tostel/assets/77918183/4ed4ee03-f06c-49c4-9cbe-c45ff7c17cb0)

Fail - the door opened

![doorover](https://github.com/sanho-is-coral/Tostel/assets/77918183/826eccbe-081f-4e87-9698-50df9b426e12)

Fail - wrong direction

![fallingover](https://github.com/sanho-is-coral/Tostel/assets/77918183/f96e51e2-03e5-4ccc-973d-2853feaabd9d)


# Animator
<img width="867" alt="Animator architecture" src="https://github.com/sanho-is-coral/Tostel/assets/77918183/7e19f8da-8f54-44a9-8faf-dfacfb2074b2">
Once external scripts affect the animation bool variable, that changes the animation status.

Four animation controllers in total.


# Bump Mapping
<img width="867" alt="Bump mapping1" src="https://github.com/sanho-is-coral/Tostel/assets/77918183/da9592b5-e177-4263-b232-79b8a726fbf0">
<img width="867" alt="Bump mapping1" src="https://github.com/sanho-is-coral/Tostel/assets/77918183/95010c66-951a-4d14-a0c7-69f2f7a24976">
<img width="867" alt="Bump mapping1" src="https://github.com/sanho-is-coral/Tostel/assets/77918183/37673890-ecc8-4c29-bc8a-398858a4738b">
