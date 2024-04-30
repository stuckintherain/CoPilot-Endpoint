# CoPilot-Endpoint
Set up your own CoPilotGPT on your VSCode. Local copilot that does not send your data to Microsoft.  

First, open VSCode and check for updates. If updates are available you will see "restart to update." Click that and VSCode will reboot and you will be using the
latest version.
![Screenshot 2024-04-30 090856](https://github.com/stuckintherain/CoPilot-Endpoint/assets/117696531/291d640b-1c2e-4084-953b-1eb99da20b08)

Now go to ollama.com and download and install ollama for your OS.
![Screenshot 2024-04-30 090740](https://github.com/stuckintherain/CoPilot-Endpoint/assets/117696531/b10e7026-7396-4a14-8c0b-4949dd9ab37b)

Open a local terminal and pull the latest metas. In the terminal enter 
'ollama pull llama3:8b' (this can take awhile.Took me about 12mins.)

When that has finished once again in the terminal pull instruct. 
'ollama pull llama3:instruct'

Next go back to VSC click extensions and search for CodeGPT

Download and install the extention that has over 1million downloads. Currently.

Click the little gear on the CodeGPT and open up the settings and select extension settings.

On the first drop down we are going to choose Ollama

Below the language drop down there is Code GPT.Autocomplete: and click the checkbox for Enable CodeGPT Copilot

On the next drop down under Code GPT.Autocomplete: Provider you will pick Ollama3:instruct

Next open up the code gpt dialog window.

At the top you will see 'Select A Model' and make sure you have Ollama3:8b

This is a pretty slow llm but it's yours!

