# OllaMail
A Windows console email client ![powered_by_ollama](https://github.com/perpendicularai/OllaMail/assets/146530480/e3fb2a1a-de87-422e-8db6-bf3fee076f81)

## Project Background
The idea of having to read endless amounts of email is cumbersome, many may agree that their inbox is a sheer mess. To address this dilemma, we make use of generative ai to formulate a response to an email read using imap. This debatebly eliminates skipping or missing an email and can help drive the challenge towards inbox zero. Furthermore, it is strongly inspired by the Semantic Kernel's Function Calling [Stepwise](https://github.com/microsoft/semantic-kernel/blob/main/python/samples/getting_started/05-using-the-planner.ipynb) Planner by [Microsoft](https://www.microsoft.com)

## Getting started
- Firstly, you'll need to have the (1) mail server address for your email server, (2) the email accounts you would like to log into and (3) the password. Imap uses port 587, which is hardcoded as default.
- Ensure that you have [Ollama](https://ollama.com/download) installed and running Meta's [llama3](https://llama.meta.com/llama3/) , served on the device you are running the email client on. The api endpoint is hardcoded as http://localhost:11434/api/generate.
- Once that has been done, download the repo as a zip archive, extract the contents and install it using powershell. This will install it as a program on your device and can be launched from the start-menu. See below:
![test_1](https://github.com/perpendicularai/OllaMail/assets/146530480/0e62d37e-2859-4118-a10a-3c3ade7fdbd5)

## Current features
- send> : Sends an email
- edit : Presents a prompt to generate a new reply to the email
- skip : Mark email as unread

### Please Note:
- The max email size that can be read is 50 KB
### Features to be added
- reading emails larger than 50kb
- downloading and viewing attachments
