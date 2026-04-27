# EduMentor.AI

### Personalized AI Tutor & Intelligent Grading System powered by Gemma 4

---

## Overview

**EduMentor.AI** is an AI-powered education platform that delivers **personalized learning experiences** and **automated grading assistance** using **Gemma 4**.

It addresses two major challenges in modern education:

* Lack of personalized learning for students
* High grading workload for teachers

---

## Problem Statement

Traditional education systems:

* Follow a one-size-fits-all approach
* Provide delayed or limited feedback
* Overburden teachers with manual grading

This leads to reduced learning effectiveness and scalability issues, especially in **low-resource environments**.

---

## Solution

EduMentor.AI introduces a dual AI system:

### Personalized AI Tutor

* Explains concepts based on student grade level
* Provides examples and practice questions
* Adapts explanations dynamically

### Automated Grading System

* Evaluates student submissions using rubric-based scoring
* Generates structured feedback
* Allows teacher review and approval

---

## System Architecture

```
Frontend (Blazor / React)
        |
.NET 8 Web API
        |
Application Services Layer
        |
Gemma 4 AI Integration Layer
        |
SQL Server Database
``

## Tech Stack

* **Backend:** .NET 8 Web API (C#)
* **Frontend:** Blazor / React
* **Database:** SQL Server
* **AI Model:** Gemma 4
* **Architecture:** Clean Architecture (Layered)

---

### Project Structure

```
EduMentor.AI.sln

/src
  EduMentor.Api
  EduMentor.Application
  EduMentor.Domain
  EduMentor.Infrastructure
  EduMentor.AI

/frontend
  EduMentor.Web

/tests
  EduMentor.Tests
```

## API Endpoints

### Tutor API

```
POST /api/tutor/ask
```

**Sample Request**

```json
{
  "studentId": 1,
  "subject": "Math",
  "gradeLevel": "5",
  "question": "What are fractions?"
}
```

### Grading API

```
POST /api/grading/evaluate
```

**Sample Request**

```json
{
  "assignmentId": 1,
  "studentAnswer": "Photosynthesis is when plants make food using sunlight",
  "rubric": "Accuracy (5), Clarity (5), Completeness (5)"
}
```
## Use of Gemma 4

Gemma 4 is used for:

* Natural language understanding
* Personalized tutoring responses
* Rubric-based grading and feedback
* Structured output generation

---

### Prerequisites

* .NET 8 SDK
* SQL Server
* Visual Studio 2022

### Students

* Personalized learning experience
* Immediate feedback

### Teachers

* Reduced grading workload
* Better student insights

### Society

* Scalable and inclusive education
* Supports low-resource environments

---

## Future Enhancements

* Voice-based AI tutor
* Multilingual support
* Student performance analytics
* Offline/edge deployment
* LMS integrations

### Product License

--- This project is licensed under the MIT License.

### Author / Developer: Vijaya Laxmi Kumbaji - Principal Software Engineer | AI/ML Programmer



---
