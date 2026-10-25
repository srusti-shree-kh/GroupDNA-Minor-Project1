
# GroupDNA – WhatsApp Group Chat Analytics

## Project Overview

GroupDNA is a Python-based WhatsApp group chat analytics project that analyzes messaging activity, communication patterns, word frequency, response times, silent streaks, and participant personality archetypes.

The project uses Python fundamentals and NumPy to transform a synthetic WhatsApp chat dataset into a structured, informative, and visually formatted analytics report.

## Project Objectives

- Parse WhatsApp group chat messages and extract relevant information.
- Generate an overview of group messaging activity.
- Calculate individual participant statistics.
- Identify frequently used words across the group.
- Visualize hourly messaging activity using a NumPy-based heatmap.
- Calculate response times and identify silent streaks.
- Assign personality archetypes to group participants.
- Generate a well-formatted final analytics report.

## Technologies Used

- Python
- NumPy
- Jupyter Notebook
- Google Colab
- Python fundamentals: lists, dictionaries, sets, tuples, loops, conditionals, and functions
- Datetime module for timestamp parsing and time calculations

## Core Project Features

### 1. Chat Parser

Reads the WhatsApp chat dataset and extracts timestamps, sender names, and message text. Identifies valid messages while handling system messages, media-omitted entries, and deleted messages.

### 2. Group Overview

Generates an overview of the group, including total messages, date range, number of participants, total duration, and individual message counts ranked from highest to lowest.

### 3. Per-Person Statistics

Analyzes individual participant activity by calculating message counts, word counts, and average message length to understand each member's contribution to group conversations.

### 4. NumPy Activity Heatmap

Creates a NumPy matrix representing message counts for each participant across the 24 hours of a day. Displays a text-based heatmap using different shading characters to identify peak activity periods and individual messaging patterns.

### 5. Top Words and Word Frequency

Counts the frequency of words used across group conversations. Normalizes words to lowercase, removes punctuation, excludes common stop words, and identifies the most frequently used words.

### 6. Response Speed and Silent Streaks

Calculates average response times for group members and identifies their longest periods of consecutive inactivity. Highlights the fastest and slowest repliers and participants with extended silent streaks.

### 7. Personality Archetype Detection

Assigns personality archetypes to participants using quantitative rules based on their messaging behavior.

The project brief defines eight archetypes:

- **The Spammer** – Frequently sends consecutive messages.
- **The Group Mom** – Uses caring and supportive keywords.
- **The Night Owl** – Is highly active late at night.
- **The Storyteller** – Sends longer messages.
- **The Drama Queen** – Frequently uses all-capital messages or multiple exclamation marks.
- **The Ghost** – Remains inactive on many days.
- **The Comedian** – Frequently uses laughter-related words.
- **The Question Master** – Frequently sends messages ending with question marks.

Each participant is assigned one primary archetype based on the highest calculated score.

### 8. Final Analytics Report

Combines the analysis into a structured, formatted report containing group statistics, participant activity, the activity heatmap, frequently used words, response patterns, silent streaks, and personality archetype assignments.

## Project Files

- `GroupDNA.ipynb` – Jupyter Notebook containing the project implementation and analysis.
- `hostel_bois.txt` – Synthetic WhatsApp group chat dataset.
- `Final Report.txt` – Final minor project report.

## How to Run the Project

1. Open the `GroupDNA.ipynb` notebook in Google Colab or Jupyter Notebook.
2. Upload the `hostel_bois.txt` dataset to the notebook environment.
3. Ensure the dataset filename and file path match those specified in the notebook code.
4. Run the notebook cells in sequence.
5. Review the generated analytics report and results.

## Dataset Description

The project uses a synthetic WhatsApp-style chat dataset representing a fictional college hostel group called *Hostel Bois 4ever*.

According to the project brief, the dataset covers 60 days, from 1 April 2024 to 30 May 2024, and contains six participants. It includes sample messages and entries such as system messages, media-omitted messages, and deleted messages for analysis.

## Project Constraints

The project is designed to demonstrate analytical problem-solving using Python fundamentals and NumPy.

- NumPy is used to create and analyze the hourly activity matrix.
- Python dictionaries are used for counting and storing statistics.
- Standard Python string methods are used for message parsing and word analysis.
- The `datetime` module is used for timestamp parsing and time calculations.
- Pandas, Matplotlib, Seaborn, Plotly, regular expressions, and pre-built WhatsApp chat analyzer libraries are not permitted under the project brief.

## Expected Outcomes

- A structured analysis of WhatsApp group activity.
- Participant-wise message and word statistics.
- Identification of frequently used words.
- A text-based hourly activity heatmap.
- Average response times and longest silent streaks.
- Personality archetype assignments for participants.
- A formatted final analytics report.

## Learning Outcomes

- Applying Python fundamentals to a practical data analytics problem.
- Using NumPy for numerical analysis and matrix operations.
- Performing exploratory analysis on messaging data.
- Calculating frequency counts and participant statistics.
- Analyzing timestamps, response gaps, and inactivity periods.
- Developing rule-based behavioral classification logic.
- Presenting analytical findings in a readable report.

## Author

**Srusti Shree K H**

## Project Information

- **Project Name:** GroupDNA – WhatsApp Group Chat Analytics
- **Project Type:** Minor Project
- **Domain:** Data Analytics
- **Dataset:** Synthetic WhatsApp-style group chat data
- **Purpose:** Academic learning and analysis of group communication patterns

---

*This project is intended for educational purposes and uses synthetic chat data.*
