# Agentic_AI_Basics

This script implements an AI-powered conversational agent that interacts with Gemini (via the OpenAI API), featuring tool integration and structured dialogue management. It includes:

- User Interaction: Captures user queries, displaying them in a formatted Rich console interface.
- Tool-Enabled Responses: Supports simulated tools like search_web and calculate, allowing AI responses to trigger external function calls dynamically.
- Persistent Context Management: Maintains a conversation history using structured message objects (via Pydantic) to ensure coherent responses.
- Loop with Exit Option: Runs continuously, processing user inputs until "quit" is entered.
- API-Based AI Execution: Requires an OpenAI API key for runtime authentication and model interaction.

Also, this script demonstrates fundamental principles of Agentic AI, where the system autonomously interprets user inputs, decides whether to invoke external tools, and dynamically integrates tool outputs into responses—an essential step toward autonomous AI agents.
