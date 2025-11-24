# AI Agents with Google's Agent Development Kit (ADK)

This project explores Google's **Agent Development Kit (ADK)** for creating AI agent workflows. These examples are based on an intensive course led by Google.

## Setup

Install dependencies: `pip install google-adk`

Create `credentials.py` with your Google API key: `GOOGLE_API_KEY = 'your-api-key-here'`

## Notebooks

- **01- Simple AI Agent**: Basic single agent with Google Search
- **02- Multi Agent Team**: Multi-agent collaboration using AgentTool
- **03- Sequential Agent**: Linear pipeline workflows (blog post creation)
- **04- Parallel Workflows**: Concurrent agent execution (multi-topic research)
- **05- Loop Workflows**: Iterative refinement cycles (story writing & critique)

## Key Components

- **Agents**: `Agent`, `SequentialAgent`, `ParallelAgent`, `LoopAgent`
- **Models**: Gemini integration with retry configuration
- **Tools**: `google_search`, `AgentTool`, `FunctionTool`
- **Runner**: `InMemoryRunner` for debugging

## Resources

- [Google ADK GitHub](https://github.com/google/adk) | [Gemini API Docs](https://ai.google.dev/docs)

