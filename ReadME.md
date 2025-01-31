# Fitness Bot - Conversational Model 
## TECHONOLOGIES
The technologies used in this application are :
- NLP Conversational Model 
    - Google Dialogflow
- Large Language Model 
    - Google Vertex AI
- Computer Vision Model
    - Roboflow YoloV8
- Web Application
    - Gradio
## ARCHITECTURE
![image](https://github.com/Niccoborg22/virtual-nutritionist-bot/assets/114749413/e9a3f9b0-03be-42f1-adaa-8c88302ed0e6)


## NLP CONVERSATIONAL MODEL
### Goal
---
The goal of the chatbot is to help people increase their nutritional awareness by creating a chatbot experience

### Technology
---
The NLP Conversational Model has been developed using the following technologies: 
- Google Dialogflow
- Python
- Node.Js

### Persona
---
The persona of this chatbot is anyone that is concerned about his health and wants to have visibility on his eating

### Future improvements
---
Some further future improvements to be implemented:
- Add identification in the frontend and change the conversational model if the user is identified
- Have a non-relational database linked to each account to keep track of each account's data
- Create a Web Application that, upon identification, visualize your data
- Deploy the application on Telegram, WhatsApp and any other medium of communication

### Intent architecture
---
The NLP Conversational Model has been developed using Google Dialogflow, the intents have been architected using the following schema: 
![image](https://github.com/Niccoborg22/virtual-nutritionist-bot/assets/114749413/62eae0d8-c5ed-420d-a8f7-d037976171fb)

Some of the answers provided by the chatbot will be returned using Vertex AI and the LLM model offered by Google. In order to do so the interaction between the Conversational Model and Vertex AI has been coded using Python.

**Entities utilized**
In order for the intents to work properly, the following entities have been created:
- @entity_foodtype: Set of all the food types that the computer vision model can recognize
- @entity_gender: Gender types, pre-built entity
- @entity_meal: Type of meal, breakfast, lunch or dinner


## COMPUTER VISION MODEL
### Goal
---
The goal of the Computer Vision Model is to recognize the food in the picture

### Technology
---
The Computer Vision Model has been developed using the following technologies: 
- Dialogflow
    - YOLOV8
- Python

### Future improvements
---
Some further future improvements to be implemented:
- Create a more accurate model by increasing the number of train images
- **ADD ANYTHING THAT WE MIGHT NEED**

## WEB APPLICATION
### Goal
---
The goal of the Web Application is to render a chat bot with which the user can interact by text and images

### Technology
---
The Web Application has been developed using the following technologies: 
- Python
- Gradio

### Images
---
![image](https://github.com/Niccoborg22/virtual-nutritionist-bot/assets/114749413/ab18161f-a0c5-43aa-82ff-5052b4afdf34)  
![image](https://github.com/Niccoborg22/virtual-nutritionist-bot/assets/114749413/6a4453a1-bda9-4d54-892b-d4a38f4ded83)


