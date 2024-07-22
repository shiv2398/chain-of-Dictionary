Here's a README for the project based on the provided content:

# AI-Powered Story Generator and Multilingual Travel Assistant
[https://www.analyticsvidhya.com/blog/2024/07/chain-of-dictionary-technique-in-prompt-engineering/](https://www.analyticsvidhya.com/blog/2024/07/chain-of-dictionary-technique-in-prompt-engineering/)

This project demonstrates the implementation of the Chain of Dictionary technique in AI applications, showcasing two main examples: a story generator and a multilingual travel assistant.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Benefits](#benefits)
- [Challenges](#challenges)
- [Future Scope](#future-scope)
- [License](#license)

## Introduction

The Chain of Dictionary method is a powerful technique in AI and natural language processing that organizes a series of linked dictionaries or JSON objects to guide AI through tasks or conversations. This project implements this technique to create two practical applications.

## Features

1. AI-driven story generator
2. Multilingual travel assistant
3. Step-by-step processing with contextual continuity
4. Image generation for each step and final output

## Installation

To run this project, you need to install the required dependencies:

```
pip install openai pillow
```

Make sure to set up your OpenAI API key as an environment variable:

```
export OPENAI_API_KEY="your-api-key-here"
```

## Usage

To use the applications, run the respective Python scripts:

1. For the story generator:
   ```
   python story_generator.py
   ```

2. For the multilingual travel assistant:
   ```
   python travel_assistant.py
   ```

## Examples

### Story Generator

The story generator creates a science fiction story in multiple steps:
1. Generate a basic premise
2. Develop the main character
3. Create a plot outline
4. Write the opening paragraph

### Multilingual Travel Assistant

The travel assistant provides information about a destination in multiple languages:
1. Suggest a popular tourist destination
2. Provide key information about the destination
3. Translate the information to French
4. Translate the information to Spanish

## Benefits

- Structured creativity
- Contextual continuity
- Flexibility and adaptability
- Greater control over AI responses

## Challenges

- Token limitations
- Maintaining coherence throughout steps
- Effective error handling

## Future Scope

- Integration with more AI models
- Expansion to more complex tasks and languages
- Improvement in error handling and edge cases
