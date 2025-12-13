# PolyTrack AI

An experimental reinforcement learning project focused on training an agent to play the browser-based game **PolyTrack** using raw screen input.

## Overview
The goal of this project is to explore **vision-based reinforcement learning under real-time constraints**, without access to game APIs or simulation environments (e.g., OpenAI Gym).

The agent learns from:
- full-screen screen capture
- a constrained action space (accelerate, turn left/right, restart)
- custom reward shaping and crash detection heuristics

## Key Challenges
- No direct game state or telemetry
- Vision-only perception using a lightweight CNN
- Latency constraints on consumer hardware (Apple Silicon)
- Manual environment handling (no Gym / SB3)

## Current Status
⚠️ **Work in Progress / Experimental**
- Core logic and architecture exploration in progress
- Training stability and reward shaping under iteration
- Codebase reflects experimentation rather than a finalized system

## Tech Stack
- Python
- PyTorch
- OpenCV
- NumPy

## Learning Outcomes
- Practical challenges of real-time RL
- Reward shaping under noisy observations
- System-level tradeoffs between accuracy and latency

## Notes
This repository is intentionally kept public as a learning and research sandbox.  
It is not a production-ready implementation.
