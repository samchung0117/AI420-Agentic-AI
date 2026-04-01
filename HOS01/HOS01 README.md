# HOS01 Execution

Assume you will be under the HOS01 directory.
cd HOS01

Activate the virtual environment.
source .venv/bin/activate


Installs all the listed packages.
pip install -r requirements.txt

Launch the dev UI.
adk web

## Testing This agent
How do you say hello in Spanish?
What's a formal greeting in Japanese?
Tell me how to greet someone in French.

## Prompt for STRIDE 
Role: You are a Senior DevSecOps Engineer specializing in Agentic AI architecture.
Context: I am developing an AI Agent in Python within GitHub Codespaces.
•	Agent Goal: “You are a helpful assistant that greets the user. Ask for the user's name and greet them by name.
•	Tools/Capabilities: “No tools are used in this project.”
•	Environment: GitHub Codespaces (Linux-based container).
Task: Perform a STRIDE Threat Model analysis specifically for this agent.
1.	Decompose the System: Identify the Trust Boundaries (e.g., User -> Agent, Agent -> Tools, Agent -> Environment).
2.	STRIDE Analysis: For each category (Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege), identify at least one Agentic-specific threat.
3.	OWASP Alignment: Map these threats to the OWASP Top 10 for Agentic AI (2026) (e.g., ASI01: Agent Goal Hijacking, ASI02: Tool Misuse).
4.	Mitigation: Provide Python-specific code snippets or configuration changes to mitigate the highest risk threats within a Codespaces environment.
Output Format: Present the findings on a Markdown table followed by a "Remediation Guide" section.

