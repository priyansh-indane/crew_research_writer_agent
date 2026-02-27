# crew_research_writer_agent

Multi-Agent Research & Writing Crew
This project demonstrates a multi-agent system built using CrewAI. It leverages two specialized AI agents to automate the process of researching a specific topic and transforming those findings into a concise, engaging blog post.

🚀 How It Works
The system utilizes a sequential workflow where:

Research Specialist: Finds 3-5 interesting and recent facts about a given topic.

Creative Writer: Takes the research output and crafts a 100-word blog summary.

🤖 The Agents
Research Specialist-->Research interesting facts about the topic: {topic}.
Creative Writer-->Write a short blog summary using the research.

📋 The Tasks
Task 1 (Research): Identifies key facts and provides a bulleted list of 3-5 items.

Task 2 (Writing): Uses the output of Task 1 as context to generate a high-quality summary.
