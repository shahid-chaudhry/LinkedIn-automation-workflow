# LinkedIn-automation-workflow

A comprehensive description of "Linkedin Automation Workflow"

🟢 Node 1 – On Form Submission
Purpose: Starts the workflow whenever a new form is submitted. The user provides a LinkedIn post topic and target audience.

🟢  Node 2 – Content Researcher (AI Agent)
Purpose: This AI agent researches topics and creates professional, engaging LinkedIn posts using real-time data from the internet. It connects to Google Gemini for writing.

🟢  Node 3 – Image Generator (AI Agent)
Purpose: Converts the LinkedIn post text into a visual image prompt that can be used with a text-to-image generator. The visuals make the posts more engaging and brand-friendly.

🟢 Node 4 – Hugging Face Image Model
Purpose: Takes the visual prompt from the Image Generator and generates a real image using the Hugging Face text-to-image model.

🟢 Node 5 – LinkedIn Post Node
Purpose: Automatically publishes the final post (text + image) directly to LinkedIn.

🟢Final Workflow Summary
1. Form Submission → User inputs topic and target audience.
2. Content Researcher → AI researches and writes post using Gemini.
3. Image Generator → AI creates an image prompt.
4. Hugging Face Model → Generates a professional image.
5. LinkedIn Node → Publishes post automatically.
