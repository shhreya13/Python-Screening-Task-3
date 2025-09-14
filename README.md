### **Research Plan**

My strategy in undertaking this assignment is to analyze and contrast two open-source language models: CodeLlama-7B and Mistral-7B, both of which are LLMs and both able to comprehend the code and produce codes. I chose CodeLlama-7B as my main model since it was code-trained and therefore robust and simple enough for a task dealing with Python code. Mistral- B is utilized as a comparative model for measuring the trade-offs of a specialized code model. I evaluate each model based on its capacity to correctly parse Python syntax, detect logical errors in student written code and produce consequential prompts. I will begin by reading through the model's documentation, sample outputs and benchmarks for understanding and reasoning of the code. My criteria for evaluation are code understanding capability, text quality and learning intent for generating hints and feedback.



I would form a small handpicked dataset of Python code samples with frequent student errors, e.g., logic, syntax and conceptual errors. For every sample, I would input the code to both the models and examine the output. I will examine the output prompt for usefulness, clarity and alignment of mine with learning objectives. My main evaluation criteria is, Does the model correctly identify the fundamental logical error and does it produce a prompt that invites students to think independently. This method will enable me to contrast both models and determine whether they are appropriate for student competence analysis. 



### **Reasoning**



**1. What makes a model appropriate for high-level competence analysis?**



A high-level competence analysis model should have the ability to properly interpret Python code, recognize logical or conceptual mistakes, and provide hints that lead students into critical thinking without giving away the answer. The model should generate concise, educationally appropriate hints and respond to various coding situations, facilitating evaluation of syntax and deeper reasoning.



**2. How would you test whether a model produces useful prompts?**



I would try the model on a handpicked collection of Python code examples with  student errors, including logical mistakes, syntax errors, and conceptual confusion. I would assess the produced prompts in terms of clarity, utility, and correspondence to learning goals. An effective prompt is one that assists the student in recognizing and comprehending their errors while fostering independent problem-solving.



**3. What are potential trade-offs between accuracy, interpretability, and cost?**



Very accurate models such as CodeLlama-7B might use a lot of computational resources, which translates to expense and could be time-consuming in responses. Lighter models such as Mistral-B are quicker and consume fewer resources but could need immediate engineering in order to meet the same pedagogical level. Interpretability is also not constant: complex outputs can be more difficult for novices to interpret, yet less complex prompts can be more intuitive but less accurate.



**4. Why did you pick the model you tested, and what are its limitations or strengths?**



I used CodeLlama-7B as the main model since it's trained solely on code and has powerful code understanding and reasoning. Mistral-B is used as a comparison model to assess flexibility and efficiency. CodeLlama-7B's strengths are high accuracy for finding errors and creating code-specific prompts, while its weaknesses are higher computational expense. Mistral-B is light and flexible but can need tailored prompt design for pedagogical utility.



#### **References**





https://arxiv.org/abs/2310.06825

https://openreview.net/pdf?id=TYStgO3Nte

https://huggingface.co/codellama

https://huggingface.co/mistral

https://huggingface.co/transformers/









.



