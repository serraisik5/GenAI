# GenAI
## Udacity generative AI projects ##


### Parameter-efficient fine-tuning project ###

* Load a pre-trained model and evaluate its performance.  <br/>
* Perform parameter-efficient fine tuning using the Hugging Face "peft" library and using the pre-trained model.  <br/>
* Perform inference using the fine-tuned model and compare its performance to the original model.  <br/>

### Custom Chatbot Project ###

I aimed to investigate recent trends in TikTok and recent informations about the company. Since GPT 3.5 is not trained on 2023 and after data, it can not be aware of recent trends. TikTok wikipedia page used as dataset.   <br/>

* Create embedding for new data  <br/>
* Use cosine similarity for retrieval  <br/>
* Provide the context in prompt to OpenAI Completion Model <br/>

### AI Photo Editing with Inpainting ###

The Segment Anything Model (SAM) is activated to create a mask around the object, choosing the most accurate mask generated. Then the user gives a text description to specify a new background for the selected object. An infill model (`diffusers/stable-diffusion-xl-1.0-inpainting-0.1`) then creates this new background, and the final image is displayed. Optionally, the user can choose to invert the mask and substitute the subject while keeping the background. 


