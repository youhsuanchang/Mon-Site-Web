---
title: "Exploring AI in Mental Health"
date: 2026-09-23
tags: ["AI", "web"]
description: "What I’m Learning from Woebot"
ShowToc: true              # Show table of contents (default: false)
TocOpen: true              # TOC starts expanded (default: false)
series: "My Series"        # Group posts into a navigable series
searchHidden: true         # Exclude from search index (default: false)
hidden: true               # Exclude from llms.txt (default: false)
cover: "/images/cover1-1.png" # Open Graph / Twitter Card image
entry-cover: "/images/cover1-1.png" # Include image in the list of article
---

Recently I’ve been exploring how AI can support mental health, starting by analyzing tools that are already in the market and have real user feedback.

In this post I’d like to share how I’ve been organizing my thoughts around Woebot, a well-known mental health chatbot, and some early reflections from a design and ethics perspective.

## What is Woebot?

Woebot is a chat-based mental health support application that can be used on both desktop and mobile devices. It is designed as a daily, approachable “check-in companion” to help people build sustainable self-care habits rather than replace human therapists.

## Clinical Approach and Core Features

Woebot is built on evidence-based methods, especially Cognitive Behavioral Therapy (CBT), a goal-driven psychological approach, and delivers them through brief, structured daily conversations.

Through chat, it guides users through scripted CBT exercises, tracks mood over time, and visualizes emotional patterns so users can see trends instead of just isolated moments.

## Technical Design

Woebot relies heavily on rule-based conversational design, combining decision trees with pre-crafted CBT flows. This makes the system highly controllable and lowers the risk of unpredictable responses.

Natural language processing (NLP) is embedded, not to generate free-form text, but to route users into the right “guided dialogue” and to detect emotionally loaded language that may signal a need for additional help.

## Ethics, Safety, and Data Protection

Woebot is very explicit about its boundaries. For example, it clearly states “I’m not a therapist,” explains that clinicians supervise content but are not present in real time, and encourages users to seek immediate human help in emergencies.

On the data side, it treats all user information as Protected Health Information (PHI), aligns with HIPAA requirements, and states that it does not sell or share user data with advertisers.

## What We Can Learn from Woebot’s Design

From a design perspective, a few patterns stand out as worth learning from:

* **Structured CBT exercises** (e.g., thought records, behavioral activation) make self-help more actionable.
* **Controlled intervention flow** and predictable conversational pacing reduce clinical risk while keeping engagement high.
* **Clear expectation setting** (“this is not therapy,” “this is not a crisis service”) prevents user over-reliance.

I’m continuing to explore other AI mental health supporting tools, open to further discussions!