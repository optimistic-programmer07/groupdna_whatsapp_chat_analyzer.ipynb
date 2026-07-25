# groupdna_whatsapp_chat_analyzer.ipynb
Python-based WhatsApp Chat Analyzer using NumPy to uncover activity patterns, participant insights, and fun group archetypes.

# 📊 GroupDNA – WhatsApp Chat Analyzer

A Python-based data analysis project that parses exported WhatsApp chat files and uncovers interesting insights about group conversations using **Python**, **NumPy**, and core data structures.

---

## 📌 Project Overview

GroupDNA transforms a raw WhatsApp chat export into meaningful statistics, activity visualizations, and fun participant archetypes.

The project demonstrates practical use of:

- File Handling
- Dictionaries
- Lists
- Sets
- Loops
- Functions
- String Processing
- Date & Time Handling
- NumPy
- Data Analysis Concepts

---

## 🚀 Features

### 📂 Chat Parser
- Parses WhatsApp exported `.txt` chat files.
- Separates:
  - Timestamp
  - Sender
  - Message
- Detects:
  - System Messages
  - Deleted Messages
  - Media Messages

---

### 👥 Group Overview
- Total messages
- Number of participants
- Chat duration
- Messages per participant
- Individual contribution (%)

---

### 📈 Activity Analysis
- Busiest day
- Busiest hour
- Most active participant
- Message distribution

---

### 🔥 Activity Heatmap (NumPy)

Creates a **Participants × 24 Hours** matrix showing when each member is most active.

Includes:

- Hour-wise activity
- Terminal text-art heatmap
- Peak active hour for each participant

---

### 📝 Word Analysis

- Top 10 most used words
- Stop-word removal
- Lowercase normalization
- Punctuation removal
- Horizontal frequency bars

---

### ⏱️ Response Analysis

Calculates:

- Average response time
- Fastest replier
- Slowest replier

---

### 🤫 Silent Streak Analysis

Finds the longest number of consecutive days each participant remained inactive.

---

### 💬 Spam Analysis

Measures:

- Average consecutive message burst
- Longest spam streak
- Consistent Spammer
- Burst Messenger

---

### 🏆 Chat Archetypes

The analyzer identifies fun personalities within the group:

- 📨 The Spammer
- ❤️ The Group Mom
- 🌙 The Night Owl
- 📖 The Storyteller
- 🎭 The Drama Queen
- 👻 The Ghost
- 😂 The Comedian
- ❓ The Question Master

---

## 🛠️ Technologies Used

- Python 3
- NumPy
- datetime

---

## 📁 Project Structure

```
GroupDNA/
│
├── hostel_bois.txt          # WhatsApp chat export
├── mini_project_1.ipynb     # Main notebook
├── README.md
```

---

## ▶️ How to Run

1. Export any WhatsApp chat.

```
WhatsApp
→ More
→ Export Chat
→ Without Media
```

2. Place the exported `.txt` file in the project folder.

3. Update the filename in:

```python
with open("hostel_bois.txt", "r", encoding="utf-8") as f:
```

4. Run the notebook.

---

## 📊 Sample Output

```
Total Messages : 1524
Participants   : 6
System Messages: 12
Media Messages : 48

Most Active Person : Rahul

Fastest Replier : Priya
Slowest Replier : Aman

THE SPAMMER
Rahul (Average Burst : 4.81)

THE NIGHT OWL
Aman (79.8%)

THE QUESTION MASTER
Neha (31.2%)
```

---

## 🎯 Learning Outcomes

This project helped me practice:

- Parsing real-world text data
- Data cleaning
- Dictionaries and Sets
- String manipulation
- Working with timestamps
- NumPy matrices
- Data visualization in terminal
- Analytical thinking using Python

---

## 📜 Future Improvements

- Matplotlib visualizations
- Word Cloud generation
- Emoji analysis
- Sentiment Analysis
- Interactive Dashboard
- CSV/PDF report generation

---

## 👨‍💻 Author

**Agraj Ekawade**

First-Year B.Sc. Data Science Student

GitHub: *(Add your GitHub profile link here)*

LinkedIn: *(Add your LinkedIn profile link here)*

---

## ⭐ If you like this project...

Give it a ⭐ on GitHub!
