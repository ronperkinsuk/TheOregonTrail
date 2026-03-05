# The Oregon Trail - Historical Reconstruction Project

*A faithful reconstruction of the legendary educational game that defined a generation*

## 🎯 Project Overview

This repository contains multiple implementations of **The Oregon Trail**, the iconic educational game that taught millions of students about 19th-century American history. Originally created in 1971 by Don Rawitsch, Bill Heinemann, and Paul Dillenberger, this project presents faithful reconstructions across different platforms and technologies.

## 📚 Historical Significance

### The Original Game (1971)
- **Created by**: Don Rawitsch, Bill Heinemann, and Paul Dillenberger
- **Platform**: HP 2100 minicomputer with teleprinters
- **Purpose**: Educational tool for 8th-grade history students at Jordan Junior High School, Minneapolis
- **Development time**: Just two weeks!
- **Impact**: Over 65 million copies sold, World Video Game Hall of Fame inductee

### The Journey
The game simulates the perilous 2040-mile journey from Independence, Missouri to Oregon City, Oregon in 1847. Players must manage supplies, hunt for food, deal with random events, and make strategic decisions to survive the American frontier.

## 🗂️ Repository Contents

### 1. **oregon1978.bas** - Original HP BASIC Reconstruction
- **Source**: Creative Computing magazine (July-August 1978)
- **Platform**: HP Time-Shared BASIC
- **Features**: Complete original game logic with historical accuracy
- **Notable**: Uses HP BASIC's unique `GOTO <var> OF` syntax

### 2. **oregon_c64.bas** - Commodore 64 Port
- **Platform**: Commodore 64 BASIC 2.0
- **Adaptations**: 
  - RND() function for C64 timing
  - ON...GOTO instead of GOTO <var> OF
  - C64-specific string handling
  - TI-based shooting mechanics

### 3. **oregon_spectrum.bas** - Sinclair Spectrum Port
- **Platform**: Sinclair Spectrum BASIC
- **Adaptations**:
  - LET statements for variable assignments
  - TIME-based shooting mechanics
  - Spectrum-compatible random number generation

### 4. **oregon-trail.html** - Modern Web Implementation
- **Technology**: HTML5, CSS3, JavaScript
- **Features**:
  - Faithful recreation of original game mechanics
  - Retro terminal aesthetic with CRT scan lines
  - Interactive shooting mini-games
  - Historical sidebar with game trivia
  - Responsive design

## 🎮 Game Mechanics

### Core Gameplay
- **Objective**: Guide a family of five pioneers 2040 miles to Oregon
- **Duration**: 5-6 months (in-game time)
- **Budget**: $700 after purchasing a $200 wagon
- **Resources**: Oxen, Food, Ammunition, Clothing, Miscellaneous Supplies

### Key Features
- **Supply Management**: Balance food, ammunition, and medical supplies
- **Hunting**: Timed shooting mini-games for food
- **Random Events**: 16 different events including bandit attacks, weather, and illness
- **Mountain Passages**: Special challenges at South Pass and Blue Mountains
- **Historical Accuracy**: Based on pioneer diaries and historical research

### Shooting Mechanics
The game features a unique timed shooting system where players must quickly type words like "BANG", "BLAM", "POW", or "WHAM" when prompted. Response time and accuracy determine success in hunting and combat situations.

## 🛠️ Technical Details

### Original Implementation (1971)
- **Language**: HP Time-Shared BASIC
- **Hardware**: HP 2100 minicomputer
- **Interface**: Teleprinters (no monitors!)
- **Storage**: Paper tape and punched cards

### Modern Adaptations
Each port maintains the original game logic while adapting to platform-specific requirements:

- **Variable naming**: Preserved original single-letter variables (A, B, C, F, M, etc.)
- **Game flow**: Exact replication of original decision trees
- **Random events**: Identical probability distributions
- **Mathematical formulas**: Preserved original calculations

## 🎨 Web Version Features

The HTML implementation includes:
- **Retro Aesthetic**: Green-on-black terminal styling with scan lines
- **Historical Context**: Sidebar with fascinating game history
- **Interactive Elements**: Real-time shooting challenges
- **Responsive Design**: Works on desktop and mobile devices
- **Educational Value**: Preserves the original learning objectives

## 🏆 Cultural Impact

### Educational Legacy
- **65+ million copies** sold across all versions
- **World Video Game Hall of Fame** inductee (2016)
- **Most popular educational software** in Minnesota schools (1974-1979)
- **Influenced generations** of students and game developers

### Famous Players
- **Prince** (musician) tested the original game at Bryant Junior High School
- **Thousands of students** lined up after school for their turn to play

## 🚀 Getting Started

### Web Version
Simply open `oregon-trail.html` in any modern web browser. No installation required!

### BASIC Versions
Each `.bas` file can be run on its respective platform:
- **HP BASIC**: Use an HP Time-Shared BASIC emulator
- **Commodore 64**: Load in C64 BASIC or use an emulator
- **Sinclair Spectrum**: Load in Spectrum BASIC or use an emulator

## 📖 Game Instructions

1. **Initial Setup**: Choose your shooting skill level (1-5)
2. **Purchases**: Spend your $700 on oxen ($200-$300), food, ammunition, clothing, and supplies
3. **Journey**: Make decisions each turn:
   - Hunt for food (requires ammunition)
   - Stop at forts to resupply
   - Continue on the trail
4. **Survival**: Manage your resources carefully - running out of food means death!
5. **Victory**: Reach Oregon City with your family intact

## 🎯 Educational Value

This game teaches:
- **Historical context** of westward expansion
- **Resource management** and strategic thinking
- **Probability and risk assessment**
- **Historical geography** of the American frontier
- **Pioneer life** and challenges of the 1840s

## 📜 Credits

### Original Creators (1971)
- **Don Rawitsch** - Lead programmer and history teacher
- **Bill Heinemann** - Programmer and math teacher  
- **Paul Dillenberger** - Programmer and student teacher

### 2025 Reconstruction
- **Phil Spilsbury** - Project lead and historical researcher

### Historical Sources
- **Creative Computing Magazine** (July-August 1978)
- **Jimmy Maher** - 2011 port and historical documentation
- **MECC (Minnesota Educational Computing Consortium)** - Educational distribution

## 📄 License

This project is for educational and historical preservation purposes. The original Oregon Trail game is in the public domain, and these reconstructions maintain the educational spirit of the original creators.

---

*"You have died of dysentery."* - The most famous game over message in history

**Good luck on your journey to Oregon!** 🚛🌾
