# 🖼️ TEXT-TO-IMAGE-GENERATION USING STABLE DIFFUSION

## 📌 Project Description
This project demonstrates how to generate images from text prompts using a pre-trained generative model called **Stable Diffusion**.  
The model converts natural language text into realistic images using a diffusion-based deep learning process.

## 🎯 Objective
- To understand pre-trained generative models  
- To generate images from text prompts  
- To experiment with negative prompts  
- To explore different image aspect ratios  

## 🧠 MODEL USED
**Stable Diffusion v1.5**

Stable Diffusion works by:
1. Converting text into embeddings  
2. Starting from random noise  
3. Gradually removing noise (denoising process)  
4. Producing a final image that matches the prompt  

## 📝 Prompt Used
"A chai in a traditional cup on a wet surface and having a rose flower bouquet placed left side of the cup on the same surface, HD",
"The nature on rainy day, HD"

## 🔬 EXPERIMENTS PERFORMED

### 1️⃣ Basic Image Generation
Generated image directly from the given prompt.

### 2️⃣ Negative Prompt
Used:  
`blurry, low quality`  
To improve image clarity and reduce unwanted distortions.

### 3️⃣ Aspect Ratio Change
Tested different sizes:
- 512 × 512 (Square)  
- 512 × 768 (Portrait)  
- 768 × 512 (Landscape)  

This affects image composition and layout.

## 🛠️ Technologies Used
- Python  
- Google Colab  
- Diffusers Library  
- PyTorch  
- Stable Diffusion  

## 📂 Output
The model successfully generated multiple images based on the given prompt.  
Images were saved in `.png` format.

## 📖 References
- TensorFlow Stable Diffusion Tutorial  
- DALL-E Mini Colab Notebook  
- Towards Data Science Article  
- Diffusion-Colab GitHub Repository  

## ✅ Conclusion
This project successfully demonstrates how pre-trained diffusion models can generate high-quality images from text prompts.  
The experiments show how prompt design and aspect ratio influence the final output.
