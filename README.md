# Data Extraction of Public Markets in Morocco from Minutes of Meetings Proces-Verbaux (Pvs)
## Table of contents
- [Project Overview](#project-overview)
- [Fallowed Tasks](#fallowed-tasks)
- [Public markets Pvs' source](#public-markets-pvs'-source)
- [Openai GPT-3](#openai-gpt-3)
- [LLAMA 2 api](#llama-2-api)
- [to run llama 2 localy](#to-run-llama-2-localy)
- [Summry](#summry)

## Project Overview 

In this Project, I'm going to collect information about public markets in Morocco. I'll start by gathering data and extracting text from minutes (PVs : procès verbal) or similar documents. Once we have the necessary information, we'll move on to analyzing these markets by answering a few questions. These questions include identifying the competitors, determining the market price, and understanding the purpose of the offer.

here an example of some informations that will be extract from pv  :

![Group 197](https://github.com/smdhen/Data-Extraction-of-Public-Markets-in-Morocco-from-Minutes-of-Meetings---Proc-s-Verbaux-Pvs-/assets/96498289/3ee5bd03-917e-4437-9031-49eb2101ea92)



Description: Extract relevant data from  of PVs to be provided to an LLM as a context with one or more questions to be answered based on this context in order to obtain analyzable data.

## Fallowed Tasks

- Develop an automatic scraper to access PVs of public markets.
- Extract relevant information from various file types (.doc, images, .pdf), using LLama 2 model, Replicate API (LLama 2), and OpenAI API for GPT-3.
- Clean and prepare the data in a data frame.(more details on the notebooks
  
Language: Python (pandas, OCR-pytesseract, selenium, PyPDF2, replicate API, OpenAI API, re).

## Public markets Pvs' source : 

- [Here](https://www.marchespublics.gov.ma/index.php?page=entreprise.EntrepriseAdvancedSearch&AllAnn)

## Openai GPT-3

- [api-key](https://platform.openai.com/api-keys)
- [OpenAi doc](https://openai.com/)

## LLAMA 2 api 
(Replicate - python )
- [Simple exemple on how to use Llama2](https://github.com/dataprofessor/llama2/blob/master/Llama2.ipynb)


- [SWHarden_tut](https://swharden.com/blog/2023-07-29-ai-chat-locally-with-python/)

- [replicateapi-tokens](https://replicate.com/signin?next=/account/api-tokens)

- [replicate Blog](https://replicate.com/blog/run-llama-2-with-an-api?input=python#running-llama-2-with-python)


## to run llama 2 localy 

- [huggingface doc](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/blob/main/README.md)

- [dowload the model here](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main)

- [swharden tutorial](https://swharden.com/blog/2023-07-29-ai-chat-locally-with-python/)

- [llama- google-colab](https://stackoverflow.com/questions/76986412/assertionerror-when-using-llama-cpp-python-in-google-colab)

## Summry
The approach yields excellent results in extracting relevant information from public documents using the Replicate API of a large language model employed as a question-answering model for public market analysis.

Possible analyses on this type of data with a sufficient quantity could include:

Analyzing the presence of a company or companies among competitors in different markets.

Analyzing the price at which the market is won based on the Public Category/Place of Execution.


For a future procurement need, identifying the prices proposed by different companies to win a particular type of contract (like catering services), considering factors such as time and geographical location. This analysis aims to determine if the proposed prices by companies are increasing steadily or fluctuating.


Price competitiveness analysis: Comparing prices offered by competitors, identifying price trends, detecting any market distortions.

Competitor performance analysis: Evaluating the strengths and weaknesses of competitors, identifying market leaders, spotting winning strategies.

Geographic analysis: Studying the locations of market execution sites, identifying high-potential areas, adapting strategies based on regions.



