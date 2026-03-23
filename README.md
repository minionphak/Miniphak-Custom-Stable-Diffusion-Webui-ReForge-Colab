# Miniphak-Custom-Stable-Diffusion-Webui-ReForge-Colab
Customizable Google Colab script to run the ReForge WebUI with optimized settings. This notebook is designed for users who want a tailored environment with pre-loaded models, specific extensions, and automated UI configurations.
Adjust each settings/models depend on what you want. 

Setting up:
1. Repository Setup
Run the first cell to clone the ReForge repository and prepare the environment.
<img width="986" height="64" alt="Screenshot 2026-03-23 120531" src="https://github.com/user-attachments/assets/9534d17f-7346-4761-8774-158f5ad851bd" />

2. Configure Models & Authentication
Input your model download links.
If you are downloading restricted models, ensure you paste your CivitAI API Key or Hugging Face Token in the designated fields. This cell will also mount your Google Drive to save/load data.
<img width="1082" height="765" alt="Screenshot 2026-03-23 120551" src="https://github.com/user-attachments/assets/64128a8f-3128-4685-a722-d3ea783beeb6" />

3. Extensions & Extras
Add any additional extensions, upscalers, or ADetailer models you require.
<img width="1056" height="746" alt="Screenshot 2026-03-23 120842" src="https://github.com/user-attachments/assets/8521efa1-f772-4170-9a6b-5f5235fbaf01" />

4. ArcEnCiel Extension (Optional)
Use this cell specifically for the ArcEnCiel-Extension-for-WebUI. It includes custom modifications for the Colab environment and expanded search capabilities for models like ChenkinRF, Lumina, Wan 2.1, Hunuayan, NoobAI Flux2V.

<img width="1093" height="110" alt="Screenshot 2026-03-23 120901" src="https://github.com/user-attachments/assets/f6a135c1-b660-4f38-ab01-3ef283722634" />
<img width="1909" height="702" alt="Screenshot 2026-03-23 160158" src="https://github.com/user-attachments/assets/d8c56105-ecaa-4b5a-a341-88b9e553d9ae" />
<img width="1843" height="903" alt="Screenshot 2026-03-23 160517" src="https://github.com/user-attachments/assets/258b25f3-987e-421b-a494-464b90f806a5" />

5. UI Personalization
Adjust your Gradio theme and default generation parameters to save time during your session. 
<img width="1002" height="112" alt="Screenshot 2026-03-23 120912" src="https://github.com/user-attachments/assets/6922f27e-2e5e-4a02-93c5-123a72f8b601" />

6. UI Personalization & Launch
Run the launch cell.

Wait time: Approximately 3–5 minutes for the environment to initialize.

Access: Look for the public URL: https://xxxx.gradio.live link in the output.
<img width="1094" height="166" alt="Screenshot 2026-03-23 121004" src="https://github.com/user-attachments/assets/85283360-3f97-465c-9a2d-fdcdfc3c6b4e" />
<img width="1078" height="554" alt="Screenshot 2026-03-23 122419" src="https://github.com/user-attachments/assets/04827b15-c850-41fe-a289-cc02d1505e8e" />
<img width="1919" height="1062" alt="Screenshot 2026-03-23 154813" src="https://github.com/user-attachments/assets/1b6577c8-40a9-4e2b-8d40-c5241c37310e" />


T4 GPU & RAM Management

If you are using a Google Colab Free Tier (T4 GPU), please be aware of potential RAM leaks.

Issue: Switching checkpoints immediately after generating an upscaled image or using XYZ plot often triggers a crash.

