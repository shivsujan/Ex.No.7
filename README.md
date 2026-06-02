# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Aim: 

To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

# Tools Required: 

- Python 3.x  

- ChatGPT (OpenAI API / Web Interface)  

- Command-Line Interface (CLI) or simple chatbot interface  

- Text editor (VS Code / PyCharm)  

- GitHub for version control and repository upload  

# Explanation: 

Prompt: "Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."

# Procedure:

1. Define Core Requirements
   - Daily task management (add, view, delete, prioritize tasks).  
   - Scheduling reminders using natural language.  
   - Suggesting wellness tips.  
   - Answering general queries.  
   - Adaptive response system (preference learning).  

2. Construct Prompts for Each Feature
   - Task Manager  
     - “Remind me to call mom at 6 PM.”  
     - “Show me my pending tasks for today.”  
   - Scheduler  
     - “Add a meeting with the  team meeting at 9 AM.”  
     - “Do I have any free slots this afternoon?”  
   - Wellness Tips
     - “Give me a quick wellness tip for today.”  
     - “Suggest a short break activity for relaxation.”  
   - General Queries
     - “What’s the weather tomorrow at 9 AM?”  
     - “Summarize my week’s schedule in 3 bullet points.”  

3. Simulate User Interaction
   - Implement a **simple chatbot/CLI** where user inputs queries.  
   - ChatGPT processes the prompt and provides structured outputs.  

4. Collect Feedback & Adapt Responses
   - Example: If the user rejects a wellness suggestion, the assistant adapts next time.  
   - Maintain a **local memory file** (JSON/CSV) for preferences.  

5. (Optional) Integrate Basic Memory
   - Store user interaction data.  
   - Adapt tasks and suggestions automatically in future prompts. 

# EXPECTED OUTPUT:

## Example LLM Response  

### Personal Productivity Assistant Features:

#### Daily Task Manager  
- Accepts natural language tasks (*“Remind me to call mom at 6 PM”*).  
- Organizes by **priority** & **deadline**.  
- Provides **daily summaries**.  

#### Smart Scheduler
- Context-aware event scheduling.  
- Detects **conflicts/overlaps**.  
- Suggests free time slots.  

#### Wellness Tips Generator
- Suggests hydration reminders, posture breaks, quick workouts.  
- Learns preferences (e.g., walking > yoga).  

#### General Query Handling
- Responds to common queries.  
- Summarizes weekly/daily agendas concisely.

<img width="1124" height="1010" alt="image" src="https://github.com/user-attachments/assets/37d0969f-a8d8-4ac6-bea4-0559b481810e" />

# Result: 

The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:

   - Understand how to tailor LLM prompts to real-life applications.
   - Foster creativity by designing features suited to their personal or academic lives.
   - Learn prompt engineering techniques for optimal interaction with AI tools.
   - Experience the versatility and utility of generative AI in solving everyday problems.
