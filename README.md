# Mini Greenhouse Assistant 🌱

## Project Overview

Mini Greenhouse Assistant is an AI-based simulation designed to help manage plant watering in a smart greenhouse.

The system analyzes soil moisture, estimates the probability of dry soil, and recommends whether plants should be watered or left alone.

The project implements three AI algorithms studied in the AI Fundamentals course.

## Implemented AI Algorithms

### 1. Hill Climbing
Used to find the optimal amount of water by evaluating different watering options and selecting the best solution.

### 2. Bayesian Inference
Used to estimate the probability of dry soil based on an imperfect moisture sensor signal.

### 3. Markov Decision Process (MDP)
Used to select the best action (Water or Wait) by comparing expected rewards and future state values.

## Technologies

- Python
- Google Colab
- Matplotlib

## Project Features

- Soil moisture analysis
- Bayesian probability estimation
- Intelligent watering decisions
- Water amount optimization
- Data visualization dashboard
- Testing with different input scenarios

## Example Results

| Parameter | Test 1 | Test 2 | Test 3 |
|---|---:|---:|---:|
| Current Moisture | 45% | 55% | 70% |
| Dry Soil Probability | 65.85% | 65.85% | 19.15% |
| MDP Decision | Water | Water | Wait |
| Water Amount | 30 ml | 10 ml | 0 ml |

## How to Run

1. Open the `Mini_Greenhouse_Assistant.ipynb` notebook.
2. Upload or open it in Google Colab.
3. Run the code cells in order.
4. View the final decision and visualization dashboard.

## Project Limitations

This project uses simulated sensor readings, predefined probabilities, and hypothetical reward values.

It does not connect to real greenhouse equipment or physical moisture sensors.

## Author

Ramil Akataev

AI Fundamentals – Final Project
