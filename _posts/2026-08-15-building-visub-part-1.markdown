---
layout: post
title: "Building ViSub, Part 1: My First Real-World AI Project"
date: 2026-08-15 22:24:46 +0700
categories: [AI Engineering, Backend Development]
tags: [visub, ai, backend, project]
---

## Introduction

<!-- Briefly introduce yourself, ViSub, and what readers can expect from this series. -->
I'm Hung, a recently CS graduated from Vietnam. I share my developer journey for everyone. For someone who have graduated in this AI era, finding a job was really difficult, so I spent time figuring out what to learn and what to build to make sure that I keep up with the pace of technology currently evolving. This harsh job market for entry level has already been turned wild not just around the world, but also in Vietnam in 2026, when I could not apply for the position I want due to the sheer amount of candidates and the competitiveness required by the companies that are hiring.
I realized that with the help of AI, developers's role has changed into an orchestrator, forcing everyone to do more with less time by controlling the AI agents, and the wave of lay off in big tech companies has proved that viewpoint quite well. So I decided to start my own projects and treat it like a real product, no more toy project, buidling something that can be sold to real users. And here it is -- ViSub --
ViSub is localization video platform that allows users localizing the video content from original language to their native language. It is my first attempt to build a complete, real-world application instead of an isolated tutorial project.

In this series, I will document the decisions, challenges, mistakes, and lessons that shaped the project.

## Why Learn Backend Fundamentals as an AI Engineer?

<!-- Explain why building an AI model or calling an AI API is only one part of creating a useful product. -->
During my internship in Ho Chi Minh city, I witnessed firsthand how incredible AI has become at coding. It bridges the gap between mid-level and senior engineers effortlessly. However, as a recent graduate, I quickly recognize a major disconnect in my preparation. 
My university background gave me strong AI foundations - math, regression, classification, gradient descent, and evaluation metrics. I also knew basic DevOps and networking tools like Docker, Github, and DNS. But when it came to building real-world, end-to-end applications, I hit a wall. I realize I did not know how to design production databases, handle authentication and authorization, architect systems for high concurrency, or deploy AI models into full-scale software ecosystems. Knowing the algorithm is one thing; building the system that serves real users is a completely different games.

## What Is ViSub?

<!-- Describe the problem, target users, main features, and current development stage. -->
I choose a simple project but targets on real user needs. I saw young people consuming the foreign entertaining videos from Chinese platform like Tiktok a lot, and many people who doing the re-up seems to lack of tools for doing the localizing job. So I made up my mind and chose to build a solution around this problem.

A typical user flow looks like this:

1. The user uploads the videos and choose the pipeline (subttiles, translation or dubbing/ voice-over)
2. ViSub automatically does all the work, render the videos and the subtitles for user to edit if they want.
3. The user receives the final video and can download it immediately.

## Why Did I Choose This Project?

<!-- Explain your personal motivation and why this problem is worth solving. -->
To be honest,  among a thousand ideas, I didn't know what to choose or where to start. But one thing in my mind that was certain: Do it to the very end, and commit myself to build a complete product that can lift the pain point and serve real users. I didn't have the market experience, so I followed a lot of people who are doing the startups and choose the ideas that I myself could afford to solve them. I found translation market was the easy one to start, especially with the help of AI techonogies. I began to do a market research, learning how people translating the documents, images, and videos. I found the gap in how people still don't use AI solutions or use the wrong AI tools to translate the videos. Many of the current solutions have bad UX, and are not convenience for Vietnamese users. So I embraced this idea, and embarked on a new journey to complete this project.

## What Did I Learn Along the Way?

<!-- Focus on a few meaningful lessons and support each one with a concrete example. -->

I gained a lot experience while working on this project include:

- I learned about SDLC, how to build a scaffold for backend
- How to use AI agent coding like Codex and Claude Code
- How to use Github and collaborate with everyone else in the teams
- How to design a databases
- How to manage the entire project
- How to plan and track progress with Jira
- I learned about testing is not optional, it's a must
- How to deploy system
- How to collaborate and delegate tasks for people, etc.

I learned more than I could imagine. I was overwhelmed at first, but I still found a way to work and learned along the way, on the fly. 

## The Biggest Bottleneck

<!-- Explain what you expected, what happened, why it became a bottleneck, and how you found the cause. -->
During building this projects, I was too naive and did not build a SRS and SDS beforehand, so I ends up changing the Database schemas multiple times, keep reaching the quotas limitation because I don't understand the design and questions from AI when brainstorming a feature and also do not know how to leverage the entire strength of human force in the team. 
## How Did I Handle It?

Although I managed to get away with the problem with some of my workarounds and tricks, I still do not satisfy with my current level of skills. I'll reveal about them later in the following posts. 

## What Comes Next?

In Part 2, I will explain ViSub's architecture and the reasoning behind its technology choices.

## Conclusion

<!-- Summarize the central lesson instead of repeating every section. -->

Building ViSub taught me that real system is not something that can be done by talking. I only understand the surface of the technologies I used, not understand the decisions beneath every choice that real engineer would make when developing features.

ViSub is still evolving, and there are many problems left to solve. I will continue sharing both the successful decisions and the mistakes I make along the way.
