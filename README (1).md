# AI-Powered Marketing Content Pipeline

## Overview

I built this project to explore how AI can be used to automate a full marketing workflow while still keeping content personalized.

The idea is based on a fictional startup called NovaMind, which helps creative agencies automate their daily work. Instead of just generating content, I wanted to connect multiple steps together — from content creation, to audience targeting, to performance analysis — into one simple pipeline.


## What This Project Does

This system takes a topic and uses AI to generate a blog post along with three different newsletter versions tailored to different audiences.

The audiences I focused on are:

* founders (focused on growth and ROI)
* operations managers (focused on workflow and efficiency)
* creative professionals (focused on reducing admin work and staying creative)

After generating the content, the system segments users based on persona, matches them with the right newsletter, and simulates sending campaigns.

It also tracks basic performance metrics like open rate and click rate, and stores everything in a structured format.


## How It Works

The workflow is pretty straightforward:

1. Generate blog content using AI
2. Generate personalized newsletters for each persona
3. Load and segment users from a mock dataset
4. Match each segment with the right content
5. Simulate campaign sending
6. Log campaign data
7. Simulate performance results
8. Save everything into `output.json`


## Tech Stack

* Python (Jupyter Notebook)
* OpenAI API
* JSON for data storage


## How to Run

1. Open `app.ipynb`
2. Run all cells in order
3. Enter your OpenAI API key when prompted
4. The results will be saved in `output.json`


## Notes

* All user data is simulated
* Email sending is not real (just a simulation)
* Performance metrics are mocked to demonstrate the workflow

In this project, I simulated CRM functionality using structured JSON data to represent contacts, segmentation, and campaign logs.

In a real-world scenario, this system could be integrated with a CRM like HubSpot via API to create contacts, assign persona tags, and track campaign performance.



## Why I Built This

What I found interesting while building this is how this kind of system starts to look like a simple multi-agent setup.

Different parts of the pipeline are doing different jobs — generating content, organizing users, and analyzing results. Even though it’s all in one script, the structure could easily be extended into separate AI agents working together.

This feels very aligned with what Palona AI is trying to do — using AI not just for single tasks, but to manage entire workflows in a scalable and personalized way.

## Final Thoughts

What I found most interesting while building this project is how quickly a simple pipeline can start to resemble a multi-agent system.

Even though everything is implemented in one notebook, each step naturally takes on a different role — content generation, audience segmentation, and performance analysis.

I think this reflects how AI systems can evolve from single-task tools into coordinated workflows that manage entire business processes.
