Files used in the lab exercises go here.

Practical : 

URL : https://lms.godeploy.it/
Username : Student
Password : Pa55w.rd

Lab Keyword : BJ5GC8

Created Open AI  Resource Group : laguduva14003463

Common Steps : 
Create a Subscription Instance with Subscription Resource Group which Created / Allocated to you
For This Training : 
	- Subscription is CS-SUB-0483
	- Resource Group : AI-050
	- Instance Details
		○ Region : EAST US
		○ Name : laguduva14003463
		○ Pricing Tier : Standard S0
In Created Subscription Open AI Resource Instance go to Open AI Studio.
After Redirecting to Azure Studio : Create an deployment which to performance below exercises

Endpoints available in the Azure Portal section --> Open AI Instance ( Subscription ) --> Keys and endspoints. Use it
Deployment name available in the studio.

Deployment name used ==> laguduva-turbo-16k

Exercise 1 : Just a plain prompt chat exposing to the internet.
Create an Azure Open AI Resource
Open Azure Open AI Studio in new tab
Create an deployment with gpt-35-turbo-16k and 5k Token

Chat Playground to use the deployment
	- 3 Sections -- Setup, Chat Windows, Configuration
	-  Try setup to try out with different system message ( different type of people )
	-  Try Setup to try out with Examples. Chat completions will results in similar template of messages
	- In Configuration, Increase max response to atleast 1000 which make the response to use more text
	- In Configuration, Change the temperature to 0 instead of 1. Value increase with unexpected or creative responses
	- In Top Right, we can see deploy to new web app
	- After Deployment, you can launche the web app which created with initial setup and config

Exercise 2 : Creating a open chat service using gen AI. Will use the deployment in your app to check question on hiking

https://github.com/venkateshlr/openai-genai-sol-lab2
pip install --trusted-host pypi.org --trusted-host pypi.python.org --trusted-host files.pythonhosted.org openai==1.13.3
pip install --trusted-host pypi.org --trusted-host pypi.python.org --trusted-host files.pythonhosted.org python-dotenv

git config --global http.sslVerify true --> Make false to install python packages. Revert it when done


Exercise 3 : Utilize prompt engineering in your app. Python Code assistant

	1) How to use the prompt
	2) Setup --> Change the system message. Based on the system message description the prompt results will be populated. You can add real time examples in the example section.

Exercise 4 : Generate and improve code with Azure OpenAI Service

	1) Improve the code - The app for Go Fish in sample-code can be run if you replace the lines that contain bugs with the response from Azure OpenAI. If you run it without the fixes, it will not work correctly.

Exercise 5 : Generate image with DALL-E Model
Exercise 6 : Implement Retrieval Augmented Generation (RAG) with Azure OpenAI Service --> Basically answer the prompt based on the data source
