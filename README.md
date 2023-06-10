# QR-code-generative-imaging
For this project, the Stable Diffusion neural network model was used to generate images conditioned on QR code inputs via ControlNet.

## Intro

Stable Diffusion is a deep learning, text-to-image model released in 2022. It is primarily used to generate detailed images conditioned on text descriptions.[1]

ControlNet, meanwhile, is a Stable Diffusion model that lets you copy compositions or human poses from a reference image.

The capabilities of ControlNet does not stop with copying humans, however, as one can easily condition the model to take on a certain image, and filter the results of the neural network algorithm to match the image input. In other words, one can send a text prompt into the AI, and control the results using a photo or illustration with certain characteristics similar to the expected output.

## Method
This project uses the AUTOMATIC1111 Stable Diffusion GUI[3] and switches between Dreamshaper[4] and RevAnimated[5] checkpoints, aside from many others used for tests. A DPM 2++ Kerras sampling method was utilized for the output, and some other classic sampling methods such as Euler were used for practice. As of writing, ControlNet is at v1.1.223, and the possibility of multiple controls is possible. Two control images were supplied to the algorithm. 

## Results
So far I’m pretty satisfied with the results, and planning to use the images as a type of “end credits” slide for my projects/presentations.

One big problem for me though, is the processing time. It took my computer about 15 or so minutes to generate some of the QR images, and I believe my computer's specs is good enough to avoid that issue. Maybe I'll try changing the settings to avoid this runtime issue.


![QR code produced using a parametric shift](/images/QR5.jpg "Simple parametric QR")

### Contact me (in case the QR codes were not enough)
<ul>
<li> Let me know if they work or not: https://forms.gle/4WY7WdFRbqwKDmon8
<li> Github: https://github.com/ujsolon/QR-code-generative-imaging
<li> Website: https://ujsolon.com
</ul>

## References
<ol>
<li> Wikipedia. https://en.wikipedia.org/wiki/Stable_Diffusion
<li> Stable-Diffusion-Art. https://stable-diffusion-art.com/controlnet/#:~:text=ControlNet%20is%20a%20Stable%20Diffusion,the%20exact%20composition%20you%20want.
<li> AUTOMATIC1111. https://github.com/AUTOMATIC1111/stable-diffusion-webui
<li> Dreamshaper. https://huggingface.co/Lykon/DreamShaper
<li> RevAnimated. https://civitai.com/models/7371/rev-animated
</ol>