# LangChain for LLM Application Development

> 🈴Course Specifications🈴
> 

The framework to take LLMs out of the box. Learn to use LangChain to call LLMs into new environments, and use memories, chains, and agents to take on new and complex tasks.

- Learn LangChain directly from the creator of the framework, Harrison Chase
- Apply LLMs to proprietary data to build personal assistants and specialized chatbots
- Use agents, chained calls, and memories to expand your use of LLMs

🔰 Begginer | 🧑‍🏫 Harrison Chase, Andrew Ng | 📜 **Prerequisite recommendation:** Basic Python

[🔗 Course Link ](https://learn.deeplearning.ai/courses/langchain/lesson/1/introduction) 


> 🈴Course Specifications🈴
> 

The framework to take LLMs out of the box. Learn to use LangChain to call LLMs into new environments, and use memories, chains, and agents to take on new and complex tasks.

- Learn LangChain directly from the creator of the framework, Harrison Chase
- Apply LLMs to proprietary data to build personal assistants and specialized chatbots
- Use agents, chained calls, and memories to expand your use of LLMs

🔰 Begginer | 🧑‍🏫 Harrison Chase, Andrew Ng | 📜 **Prerequisite recommendation:** Basic Python

🔗 **[Course Link](https://learn.deeplearning.ai/courses/langchain/lesson/1/introduction)** 

---

> My work found here
> 

[DLAI-Short-Courses/DLAI Short Courses/LangChain for LLM Application Development at main · yazeedmshayekh2/DLAI-Short-Courses](https://github.com/yazeedmshayekh2/DLAI-Short-Courses/tree/main/DLAI%20Short%20Courses/LangChain%20for%20LLM%20Application%20Development)

---

# Models, Prompts and parsers

The Notebook here:

[DLAI - LangChain for LLM Application Development](https://learn.deeplearning.ai/courses/langchain/lesson/2/models%2C-prompts-and-parsers)

---

# Memory

### Memory Types:

**ConversationBufferMemory**

- This memory allows for storing of messages and then extracts the messages in a variable.

**ConversationBufferWindowMemory**

- This keeps a list of the interactions of the conversation over time. It only uses the lask k interactions.

**ConversationTokenBufferMemory**

- This memory keeps a buffer of recent interactions in memory, and uses token length rather than number of interactions to determine when to flush interactions.

**ConversationSummaryMemory**

- This memory creates a summary of the conversation over time.

### Additional Memory Types

**Vector data memory**

- Stores text (from conversation or elsewhere) in a vector database and retrieves the most relevant blocks of text.

**Entity memories**

- Using an LLM, it remembers details about specific entities.

**Note:** You can use multiple memories at one time.

E.g., Conversation memory +  Entity memory to recall individuals.

**Note:** You can also store the conversation in a conventional database (such as key-value store or SQL).

> **The notebook here:**
> 

[L2-Memory.ipynb](https://prod-files-secure.s3.us-west-2.amazonaws.com/2dd69c73-c909-46b6-aa19-d438cd59215e/91dec0d0-633e-4393-aa3f-4ec3d0f6bc3a/L2-Memory.ipynb)

> **or here:**
> 

[DLAI-Short-Courses/DLAI Short Courses/LangChain for LLM Application Development/LangChain_Memory at main · yazeedmshayekh2/DLAI-Short-Courses](https://github.com/yazeedmshayekh2/DLAI-Short-Courses/tree/main/DLAI%20Short%20Courses/LangChain%20for%20LLM%20Application%20Development/LangChain_Memory)

---

# Chains

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/2dd69c73-c909-46b6-aa19-d438cd59215e/7864d225-ce7e-4eba-bbd6-1cfc19c758d0/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/2dd69c73-c909-46b6-aa19-d438cd59215e/939b04ad-d476-4646-bcf0-c80769f68fe4/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/2dd69c73-c909-46b6-aa19-d438cd59215e/6257c568-4538-4d55-9f0a-9f1a7b9ddc56/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/2dd69c73-c909-46b6-aa19-d438cd59215e/c0c2ab99-9f6b-4dad-bebf-ce7ce4329282/Untitled.png)

[DLAI-Short-Courses/DLAI Short Courses/LangChain for LLM Application Development/LangChain: Models, Prompts and Output Parsers at main · yazeedmshayekh2/DLAI-Short-Courses](https://github.com/yazeedmshayekh2/DLAI-Short-Courses/tree/main/DLAI%20Short%20Courses/LangChain%20for%20LLM%20Application%20Development/LangChain%3A%20Models%2C%20Prompts%20and%20Output%20Parsers)

---

# **LangChain: Q&A over Documents**

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/2dd69c73-c909-46b6-aa19-d438cd59215e/4fc6c8bc-e4b3-496a-9fdc-8e28c7fabb72/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/2dd69c73-c909-46b6-aa19-d438cd59215e/54eb0208-6f67-4276-acba-b7da942cb101/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/2dd69c73-c909-46b6-aa19-d438cd59215e/4cd4b8f2-58fe-4e02-b3bf-6ab87b26314a/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/2dd69c73-c909-46b6-aa19-d438cd59215e/5087f0e1-15c0-4351-ba1e-2678de96d533/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/2dd69c73-c909-46b6-aa19-d438cd59215e/643dda45-1b0b-4172-ac30-9be235565e89/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/2dd69c73-c909-46b6-aa19-d438cd59215e/106f0aa4-2b64-4978-800b-0bf7affb1187/Untitled.png)

**Note:** a really common use case of the “Map_reduce” chain is for summarization, where you have a really long document, and you want to recursively summarize pieces of information in it. 

> Notebook here:
> 

[DLAI-Short-Courses/DLAI Short Courses/LangChain for LLM Application Development/LangChain: Q&A over Documents at main · yazeedmshayekh2/DLAI-Short-Courses](https://github.com/yazeedmshayekh2/DLAI-Short-Courses/tree/main/DLAI%20Short%20Courses/LangChain%20for%20LLM%20Application%20Development/LangChain:%20Q&A%20over%20Documents)

> or here:
> 

[L4-QnA.ipynb](https://prod-files-secure.s3.us-west-2.amazonaws.com/2dd69c73-c909-46b6-aa19-d438cd59215e/892dc31d-5b2f-4d12-b399-49b7917baf99/L4-QnA.ipynb)

---
