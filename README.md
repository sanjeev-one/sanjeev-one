# Hi there, I'm Sanjeev! 👋

Welcome to my GitHub profile! I'm passionate about technology, coding, and collaborating on innovative projects. Here's a little bit about what I do:

## SLAC National Lab Code

I have had the opportunity to contribute to projects at the SLAC National Accelerator Laboratory. Here are some of the projects I've worked on:

### Project 1: Modeling and optimization of the FACET-II injector with machine learning algorithms
**Description**: Published at IPAC'24 - This project focuses on enhancing the SLAC FACET-II injector's performance by integrating machine learning algorithms. Traditional physics simulations are computationally demanding, and our approach replaces these intensive computations with a machine learning model that predicts outcomes in milliseconds. This innovation enables real-time physics predictions, significantly improving operational efficiency. The core of our model is a simple feedforward neural network that predicts key parameters like beam emittance and bunch length based on various inputs. A gradient descent feature analysis of the models reveals which input parameters impact which output parameters signifcantly, aiding the development of virtual diagnostics for particle accelerators.

**Tech Stack**: Python, MATLAB, XOPT, GPT (General Particle Tracer), Lucretia, openPMD, CNSGA (Controlled Non-dominated Sorting Genetic Algorithm), Feedforward Neural Network.

**GitHub Repo**:  [[Link to paper]](https://www.researchgate.net/publication/380665428_IPAC'24_-_Modeling_and_optimization_of_the_FACET-II_injector_with_machine_learning_algorithms) [[Link to the repository]](https://github.com/sanjeev-one/FACET-II/blob/main/README.md)

### Project 2: Bmad L1 and L2 phase scan
**Description**: This project simulates beam dynamics in the FACET-II particle accelerator. It performs a double for-loop scan over L1 and L2 phases to analyze their impact on beam behavior, setting up the simulation environment, running simulations, and visualizing results in a matrix plot format.

**Tech Stack**: Python, Anaconda, Bmad, pytao, openpmd-beamphysics, numpy, matplotlib, pandas

**GitHub Repo**: [[Link to the repository]](https://github.com/sanjeev-one/bmad)

### Project 3: Online ML Modeling with Live Data
**Description**: ongoing; goal is to take containerized simulations and deploy to a seperate HPC (NERSC) and have the system talk back to another HPC (s3df) via k8s to perform ml anaylysis during injector runs.
**Tech Stack**: K8s, docker, ML, Dask 



## 🦀 Rust Cloud Development Projects

I'm also experienced in developing cloud-based applications using Rust. Here are some of my Rust projects:

### Project 1: Audio2Blog
**Description**: Audio2Blog is a serverless application that automates the process of converting recorded conversations into AI-generated blog posts. It integrates various AWS services and uses Rust for Lambda functions to handle publishing tasks. Users can upload audio files through a FastAPI endpoint, which are then processed to create a blog-style article with speaker recognition. The system provides real-time processing status updates and automatically publishes the final blog post to a specified platform via GitHub's API.
**Tech Stack**:
- **Rust**: Powers AWS Lambda functions for backend automation and integration with GitHub's API.
- **FastAPI**: Manages audio uploads and provides API endpoints for tracking processing status.
- **AWS S3**: Stores uploaded audio files securely.
- **AWS Step Functions**: Orchestrates the workflow for transcription, blog generation, and publication.
- **AWS Transcribe**: Transcribes audio files and applies speaker labeling for clarity.
- **AWS Bedrock**: Generates AI-driven blog posts based on the transcriptions.
- **GitHub API**: Automates the publishing process for generated blog posts to the target platform.
**GitHub Repo**: [Link to the repository](https://github.com/sanjeev-one/audio-to-blog/tree/main)

### Project 2: Rust Transformer Lambda
**Description**: This project features a Rust-based AWS Lambda function using the `rust-bert` library for sequence classification. The Lambda function processes input text and returns predictions from a pre-trained BERT model, with deployment facilitated by Docker to ensure compatibility with the Lambda environment.
**Tech Stack**: Rust, Docker, AWS Lambda, AWS CLI, `rust-bert`, Lambda Runtime, Simple Logger
**GitHub Repo**: [rust-transformer-docker-lambda](https://github.com/sanjeev-one/rust-transformer-docker-lambda)

### Project 3: AWS Lambda DynamoDB Logger
**Description**: This Rust-based AWS Lambda function logs commands from events into a DynamoDB table, with an option to retrieve and display the table contents. It leverages `lambda_runtime` for Lambda execution and `rusoto_dynamodb` for interacting with DynamoDB, providing command logging and data retrieval functionalities within serverless infrastructure.
**Tech Stack**: Rust, AWS Lambda, DynamoDB, AWS X-Ray, CloudWatch, `rusoto_dynamodb`, `lambda_runtime`
**GitHub Repo**: [rust-lambda-X-db](https://github.com/sanjeev-one/rust-lambda-X-db)

## 🚀 Hackathon Projects

### Project 1: Lola (Learn Online, Like Actually)
**Description**: Developed for HackMIT 2023, Lola (Learn Online, Like Actually) is an AI-powered tutor designed to provide personalized learning experiences by harnessing YouTube content. Lola uses a **Retrieval-Augmented Generation (RAG)** memory system that updates dynamically from YouTube video transcripts, allowing it to build an organized knowledge base. Lola intelligently determines when it needs additional information from YouTube, automatically searching for relevant content and integrating it into its memory. When answering a student's question, it provides precise, timestamped responses, directing the learner to exact moments in videos that address their queries. This approach enables efficient, targeted learning on any subject, from beginner to advanced levels, with the feel of a one-on-one tutoring session.

**Tech Stack**: Faiss, FastAPI, OpenAI, Python, Tailwind, Weaviate, YouTube API

**GitHub Repo**: *Private*
### Project 2: Incognito
**Description**: Developed for Stanford's TreeHacks 2024, Incognito is a privacy-awareness tool designed to illustrate the alarming ease with which personal data can be accessed from a single photograph. By starting with just a snapshot, Incognito leverages DeepFace for facial processing, matching the image with LinkedIn profiles to pull detailed personal information, including education, job history, experiences, and more. For further accuracy and detail, it uses the Melissa Personator API to gather information such as address, home value, and property ownership details. This project underscores the rapidly vanishing privacy in the digital age, demonstrating that if a weekend hackathon project can achieve such data exposure, the boundaries of personal privacy are eroding at an unprecedented rate.

**Tech Stack**: Docker, Flask, Gunicorn, JavaScript, Makefile, Python, React Native, Together AI, Intel Dev Cloud, DeepFace, Melissa API, Fetch AI

**GitHub Repo**: *Private*



## 📫 How to reach me

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/sanjeev-one) or email me at [inquiries@sanjeev.one].

