# EDUBOT-Facial-and-Body-Movement-Recognition

https://mobileiotdata.com


A research-grade computer vision project for educational robotics. This system detects facial and body movement cues to estimate interaction readiness and engagement proxies in classroom-like environments

## Motivation
Educational AI should use non-verbal context responsibly. This project builds a modular perception layer that helps EDUBOT respond to raised hands, attention shifts, posture changes, and confusion candidates.

## Research Question
Can computer vision models reliably detect facial and body movement cues relevant to student engagement and classroom interaction in practical educational robotics settings?

## Core Use Cases
- Detect hand raise, wave, and pointing gestures
- Track face orientation and attention proxies
- Estimate posture states such as leaning forward or slouching
- Produce explainable event outputs for EDUBOT behaviors
- Summarize session-level attention and participation trends

## Architecture
1. Video input (webcam/video/stream)
2. Detection (face/person/pose)
3. Tracking (short-term person IDs)
4. Feature extraction (landmarks, angles, motion)
5. Recognition (expression, gesture, posture)
6. Fusion (multimodal and temporal logic)
7. Outputs (events, logs, API)
8. Analytics (session summaries)

