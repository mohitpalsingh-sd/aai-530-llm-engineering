# General Assignment Instructions

In this course, assignments are designed as scaffolded engineering briefs rather than traditional coding worksheets. You will usually be given a starter notebook, a specific expected outcome, and several required intermediate deliverables. However, you will have flexibility in the tools, models, prompts, implementation strategies, and evaluation methods you use to reach that outcome.

The goal is not simply to fill in missing code. The goal is to build, test, evaluate, document, and reflect on an applied LLM system or workflow.

## Repository Setup

All assignment notebooks for this course are hosted in the following GitHub template repository:
https://github.com/usd-msaai/aai-530-llm-engineering

At the beginning of the course, create your own private repository from this template.
1. Go to the course repository: https://github.com/usd-msaai/aai-530-llm-engineering
2. Click **Use this template** and create a new repository under your own GitHub account.
3. Make your repository **private**.
4. Add your instructor’s GitHub account as a collaborator.
5. Clone your private copy of the repository to your local machine or open it in your preferred coding environment.

You will use this same repository throughout the course. 

## Working with Assignment Notebooks

Each module’s assignment will have its own Jupyter notebook in the course repository. The notebooks are structured to guide your work, but they are not traditional step-by-step coding worksheets.

For each assignment, you should:
1. Open the assigned notebook.
2. Read the assignment overview and expected outcomes carefully.
3. Complete all required code sections, written questions, tables, reflections, and outputs.
4. Use the notebook structure provided unless the assignment explicitly gives you permission to reorganize it.

Do not create your own notebook or `.py` file from scratch, as this can lead to missed requirements and complicate grading.

Some assignments may ask you to create helper functions, compare multiple models, evaluate outputs, document prompts, collect test cases, or write a short recommendation. You may make reasonable implementation choices, but your final submission must address all required parts of the notebook.

## Use of AI Assistants

You are required to use AI assistants such as ChatGPT, Gemini, Claude, GitHub Copilot, or similar tools while completing assignments in this course. LLM engineering is often done with the support of AI tools, and learning how to use these systems effectively is part of the course.

However, AI tools should support your learning, not replace it.

You are responsible for:
- understanding the code and explanations you submit
- testing AI-generated suggestions before relying on them
- identifying and correcting errors
- adapting AI-generated content to the specific assignment requirements
- documenting how AI tools contributed to your work

Submitting AI-generated code, written answers, or analysis without sufficient understanding, modification, and attribution is unacceptable.

Each assignment will include an AI-use reflection section. In that section, you should explain:
- which AI assistant or assistants you used
- what you asked the assistant to help with
- what suggestions were useful
- what the assistant got wrong, left unclear, or failed to consider
- what you changed, verified, or decided yourself

## API Keys and Sensitive Information

Many assignments in this course may involve API keys, tokens, environment variables, or other private credentials.

Do not include private keys, API tokens, passwords, or other secrets in your notebook, GitHub repository, or Canvas submission.

Use environment variables, `.env` files, or other secure configuration methods when appropriate. If you use a `.env` file, make sure it is listed in `.gitignore` and is not committed to GitHub. If you are unfamiliar with this workflow, this is a great question to ask your AI Assistant.

Before submitting your work, check your notebook and repository carefully to confirm that no private credentials are visible.

## GitHub Expectations

You are expected to commit and push your work regularly.

Your GitHub repository should include:
- your completed assignment notebooks
- any supporting files required to run your work (data files are not required and should be added to your .gitignore)
- clear file organization
- no unnecessary large files no private API keys or secrets (again, do not upload data files to GitHub
- enough documentation for your instructor to understand your work

For each assignment, make sure your final version has been committed and pushed to GitHub before submitting in Canvas.

## Canvas Submission

For each assignment, submit the following in Canvas:
- A PDF version of your completed notebook.
- A link to your private GitHub repository in the submission comment.
- Any additional notes needed to understand or run your work.

Your PDF should show all required code, outputs, written answers, tables, and reflections. Before exporting to PDF, restart and rerun your notebook if possible so that the submitted version is clean, organized, and reproducible.

## Written Responses

Written responses should be clear, specific, and connected to evidence from your work. Avoid vague answers such as “the model did well” or “the prompt was better,” as well as generic or theoretical answers such as “this method should produce effect X” without tying it back to your specific results.

Instead, explain specifically what you observed and why it matters. In this course, your reasoning and interpretation are just as important as your code.
