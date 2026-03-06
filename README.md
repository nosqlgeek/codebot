# Codebot

Use local large language models in customizable coding workflows.

## Introduction

While local models work well for basic tasks, they often lack the capability to autonomously execute complex development tasks. Modern agentic development tools address this limitation by using LLMs to generate code through iterative feedback loops, following this process:

1. **Load Context**: Import existing source code into the model's context
2. **Understand Requirements**: Analyze the specification of what needs to be implemented
3. **Generate Tests**: Create test cases that validate the requirements
4. **Generate Code**: Produce source code that satisfies the specification
5. **Execute Tests**: Run the generated tests against the implementation
6. **Iterate**: Return to step 4 if tests fail, or to step 2 if additional context is needed

There are indeed already tools avialable (e.g., Aider or Zed), but I find it appealing to play around with some of the mechanics by myself:

* Customization: Tailor the workflow exactly to your needs
* Learning: Deep understanding of how agentic coding works
* Flexibility: Experiment with unique features not found in existing tools
* Integration: Build specifically for your development environment
