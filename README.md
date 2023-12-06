# doceasy

**DocEasy** is a tool which helps developers to document their code easily without any effort, whatever the language this tool will document it.

We plan to implement it using vs code extension and google cloud vertex ai, specifically its code chat model which can be used to generate documentation for any given code.

### Tools Used :
- Node.js
- Google Cloud Vertex Ai

## Implementation
1. Setup environment for creating Extension
2. Setup API and other Setups in Google Cloud
3. Import required dependencies in VS Code
4. Get selected text from editor using VS Code module
5. Pass it to the API and get the output
6. Fine tune the output giving proper prompts
7. write the output just before the code as a comment.
