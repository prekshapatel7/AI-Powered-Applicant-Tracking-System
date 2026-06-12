# AI Resume Analyzer

An AI-powered Resume Analyzer built using React, JavaScript, PDF.js, and the Gemini API. The application allows users to upload a PDF resume, extract its content, and receive AI-generated feedback including ATS score, strengths, weaknesses, missing skills, and interview questions.

## Features

* Upload PDF resumes
* Extract text from PDF files using PDF.js
* Analyze resumes using Gemini AI
* Generate ATS-style feedback
* Identify strengths and weaknesses
* Suggest missing skills
* Generate interview questions based on the resume
* Simple and clean single-page interface

## Tech Stack

### Frontend

* React
* JavaScript
* Vite
* PDF.js (`pdfjs-dist`)

### AI Integration

* Gemini API

## Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
cd resume-analyzer
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Create Environment Variables

Create a `.env` file in the root directory:

```env
VITE_GEMINI_API_KEY=YOUR_GEMINI_API_KEY
```

### 4. Start the Development Server

```bash
npm run dev
```

## Learning Outcomes

This project was built to strengthen practical React and JavaScript skills by working with real-world concepts such as file processing, API communication, state management, and AI integration.

