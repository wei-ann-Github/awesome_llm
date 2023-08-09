# AWESOME LLM

The myraid of repos, articles, tutorials etc. on LLMs is truly overwhelming. In this repo, I try to keep a curate list of awesome frameworks, libraries, software, blogs and resources for Large Language Models (LLM) that I have come across.

- [AWESOME LLM](#awesome-llm)
    - [General](#general-home)
    - [Data](#data-home)
    - [Pre-trained LLMs](#pre-trained-llms-home)
    - [Chat Bots Interface](#chat-bots-home)
    - [Fine Tuning](#fine-tuning-home)
    - [Building Applications](#building-applications-home)
    - [Prompting](#prompting-home)
    - [Vector Databases](#vector-databases-home)
    - [Serving](#serving-home)
    - [Production](#production-home)
    - [Tools Made Using LLMs](#tools-made-using-llms-home)
    - [Tutorials](#tutorials-home)
    - [Courses](#courses-home)
    - [Blogs](#blogs-home)
    - [Precautionary Tale](#precautionary-tale-home)
    = [Others](#others-home)

## General ([home](#awesome-llm))

- [The Practical Guides for LLMs](https://github.com/Mooler0410/LLMsPracticalGuide)

## Data ([home](#awesome-llm))

- Get Your Own Data
    - [Auto Label](https://github.com/refuel-ai/autolabel)
- Instruction Dataset
    - [Flan-Mini](https://huggingface.co/datasets/declare-lab/flan-mini) by Declare-Lab

## Pre-trained LLMs ([home](#awesome-llm))

- LM Trained
    - [Llama-2](https://www.interconnects.ai/p/llama-2-from-meta)
        - [Understanding LLaMA-2 Architecture & its Ginormous Impact on GenAI](https://medium.com/towards-generative-ai/understanding-llama-2-architecture-its-ginormous-impact-on-genai-e278cb81bd5c)
    - [OpenLlama](https://github.com/openlm-research/open_llama)
    - [tiiuae/falcon-7b](https://huggingface.co/tiiuae/falcon-7b)
        - 1,500B tokens of RefinedWeb enhanced with curated corpora
        - Apache 2.0 License
- Instruction Tuned
    - [flacuna](https://github.com/declare-lab/flacuna)
- Chat
    - [Llama-2 Chat](https://www.interconnects.ai/p/llama-2-from-meta)

## Chat Bots ([home](#awesome-llm))

- [ChatGPT](https://chat.openai.com/) by OpenAI
- [HuggingChat](https://huggingface.co/chat/) by HuggingFace
- [Oobabooga Text Generation WebUI](https://github.com/oobabooga/text-generation-webui)
    - [Extensions](https://github.com/oobabooga/text-generation-webui-extensions)

## Fine Tuning ([home](#awesome-llm))

- [Huggingface PEFT methods](https://github.com/huggingface/peft)
- [LOMO: LOw-Memory Optimization](https://github.com/OpenLMLab/LOMO)
    - 3 different approaches - LOMO, LoRA, and LoRA + LOMO.
- [Making evaluating and fine-tuning LLaMA models with low-rank adaptation (LoRA) easy.](https://github.com/zetavg/LLaMA-LoRA-Tuner)

## Building Applications ([home](#awesome-llm))

- [MiniChain](https://github.com/srush/MiniChain)
- [LangChain](https://python.langchain.com/en/latest/index.html) framework for a range of applications powered by LLMs
    - [course](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/)
- [Romeo GPT](https://github.com/fmanrique8/romeo-gpt) for Document Analysis and Management

### Courses

- [Building Systems with the ChatGPT API](https://www.deeplearning.ai/short-courses/building-systems-with-chatgpt/)

## Prompting ([home](#awesome-llm))

- ReAct: Reasoning and Acting [Paper](https://arxiv.org/pdf/2210.03629.pdf)
- [Legal Prompt Engineering](https://www.legalpromptguide.com/1.-introduction-to-legal-prompt-engineering-lpe)

### Courses

- [ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)

## Vector Databases ([home](#awesome-llm))

- [HyperDB](https://github.com/jdagdelen/hyperdb)
- Facebook AI Similarity Search, FAISS

## Serving ([home](#awesome-llm))

- [Ray Serve](https://docs.ray.io/en/latest/serve/index.html)

## Production ([home](#awesome-llm))

- Monitoring
    - With LangKit [Video](https://www.youtube.com/watch?v=DLJ8m3wMJrs)

### Courses

- Evaluation
    - [Evaluating and Debugging Generative AI](https://www.deeplearning.ai/short-courses/evaluating-debugging-generative-ai/)
- Debugging
    - [Evaluating and Debugging Generative AI](https://www.deeplearning.ai/short-courses/evaluating-debugging-generative-ai/)

## Tools Made Using LLMs ([home](#awesome-llm))

- " label, clean and enrich text datasets with any Large Language Models (LLM) of your choice." [Link](https://github.com/refuel-ai/autolabel)

## Tutorials ([home](#awesome-llm))

- Building an LLM open source search engine in 100 lines using LangChain and Ray [Link](https://www.anyscale.com/blog/llm-open-source-search-engine-langchain-ray)
- [Getting Started With LlamaIndex](https://zilliz.com/blog/getting-started-with-llamaindex)
- [OpenAI API Cookbook](https://github.com/openai/openai-cookbook/tree/main)

## Blogs ([home](#awesome-llm))

- Prompting:
    - [Evolution of Prompt Engineering](https://www.linkedin.com/pulse/evolution-prompt-engineering-reza-bonyadi)
    - [Prompting Guide](https://www.promptingguide.ai/techniques/knowledge)
    - [Prompt Injections](https://vickieli.medium.com/hacking-llms-with-prompt-injections-6a5ebffb182b)
- Vector Databases:
    - [Vector Databases: The Unseen Heroes of LLM and CV Applications](https://pmanrique001.medium.com/vector-databases-the-unseen-heroes-of-llm-and-cv-applications-c2246d7cf29f)
    - [Maximizing the Potential of LLMs: Using Vector Databases](https://www.ruxu.dev/articles/ai/vector-stores/)
- Building Applications:
    - [Patterns for Building LLM-based Systems & Products](https://eugeneyan.com/writing/llm-patterns/)
    - [Leveraging FastAPI, OpenAI, and SQLAlchemy for Natural Language SQL Queries](https://medium.com/@lgutierrwr/leveraging-fastapi-openai-and-sqlalchemy-for-natural-language-sql-queries-89052547289f)
    - [Creating a Chatbot with FalconAI LangChain and Chainlit](https://www.analyticsvidhya.com/blog/2023/07/creating-a-chatbot-with-falconai-langchain-and-chainlit/#h-creating-the-chat-application)

## Precautionary Tale ([home](#awesome-llm))

- [Jul 2023 Is GPT-4 Getting Worse Overtime?](https://www.aisnakeoil.com/p/is-gpt-4-getting-worse-over-time?utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-_LD-sMoG8wc3nypgPhSFaqdIgmhEtkTsUPeRqnSpnO5nOjqOq4AilthqCKjeO3qVrdPqWB)
    - [Paper](https://arxiv.org/abs/2307.09009)
- [June 2023 Google Tells Employees to Stay Away from Its Own Bard Chatbot](https://gizmodo.com/google-tells-employees-to-stay-away-from-its-bard-chatb-1850542824)
- [April 2023 ‘hallucination problems’ still plague A.I. tech](https://fortune.com/2023/04/17/google-ceo-sundar-pichai-artificial-intelligence-bard-hallucinations-unsolved/)
- [Cyber Threats](https://www.bleepingcomputer.com/news/security/cybercriminals-train-ai-chatbots-for-phishing-malware-attacks/)

## Others ([home](#awesome-llm))

- 03 Aug 2023 [ChatGPT Release Notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)