# Bringing 'Friends' characters to life

![alt text](https://play-images-prod-ctf.tech.tvnz.co.nz/api/v1/web/image/3CLEzO37tocxCoSmzzcxwx/2733ae58689b3e59e477a86d2da48a36/friends-showtile.png.2733ae58689b3e59e477a86d2da48a36.jpg?width=1200&height=630)

## Inspiration 
---
I have been inspired by numerous Conversational Artifical Intelligence technologies and stumbled upon [someone](https://github.com/RuolinZheng08/twewy-discord-chatbot) who wrote about their experience with creating a fictional character that is capable of chatting with them, intelligently. 

So, me being interested in Machine Learning and it's futuristic technologies, gave it a shot and after scrapping the web for years of scripts, watching the tutorial, endless debugging and tweaking of some parameters here and there, I have finally created a [discord server](https://discord.gg/Dy99JRS2R6) where anyone can chat with these bots. 

As I have always been a huge fan of the TV series "Friends", I instantly created some of the main characters in this ten year long series.

## Technology Used
--- 
 
The technology I have used here is Generative Pre-trained Transfomer, specifically Microsoft's pre-trained GPT, DialoGPT-medium. I attempted to train it on large but any online cloud platform and my 16GB RAM local computer could not handle the excessive number of parameters and could not train on the whole dataset. 

Hosting the model was done on HuggingFace and made sure to keep it running. 

## Platforms Used
---

* https://replit.com
* https://huggingface.co/
* https://uptimerobot.com/

## Resources
---

* Friends_script.csv is the filtered csv files containing the scripts from the first episode to the last.
* keep_alive.py and main.py is used for the replit platform to run the bots. 
* model_train_upload_workflow.ipynb is used to train and upload the model to the HuggingFace platform.

## Credit
---
Without these help I would not have been able to create this at all, so please do check them out.
* [RuolinZheng08](https://github.com/RuolinZheng08/twewy-discord-chatbot) 
* [FreeCodeCamp Tutorial by her]("https://www.freecodecamp.org/news/discord-ai-chatbot/")
