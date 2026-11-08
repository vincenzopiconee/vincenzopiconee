<div align="center">

# Vincenzo Picone
**Double MSc Student in Computer Science & Digital Innovation | Software Engineer**

Madrid, Spain & Milan, Italy

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vincenzo--piconee-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vincenzo-piconee)
[![GitHub](https://img.shields.io/badge/GitHub-vincenzopiconee-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/vincenzopiconee)

</div>

---

## Current Status

Currently pursuing a **Double Master of Science** in **Computer Science & Digital Innovation** through the **EIT Digital Master School**:
* **Year 2 (2026–2027)**: [Universidad Politécnica de Madrid (UPM)](https://www.upm.es/) — *MSc in Digital Innovation (Human-Computer Interaction & Design, Minor in Innovation & Entrepreneurship)*
* **Year 1 (2025–2026)**: [Politecnico di Milano](https://www.polimi.it/) — *MSc in Computer Science & Engineering* 

---

## Selected Systems & Engineering Portfolio

This catalog indexes all key public repositories across diverse domains to provide a complete overview beyond GitHub's pinned repository limit.

### 1. Cloud AI & Distributed Platforms

#### [DuoSigna](https://github.com/vincenzopiconee/DuoSigna) — AI-Powered ASL Interactive Learning Platform
* **Overview**: Cloud-native American Sign Language (ASL) learning system pairing real-time computer vision inference with an autonomous conversational AI tutor.
* **Architecture**: Deployed on Google Cloud Run via Docker, utilizing FastAPI for asynchronous gesture classification, MediaPipe Holistic for client/server 3D hand and pose tracking, and PostgreSQL (Neon) for persistence. Integrates Llama 3.3-70B on Groq for voice-guided pedagogical feedback.
* **Stack**: Python, FastAPI, TensorFlow, Scikit-learn, MediaPipe, Nuxt 3, Vue 3, PostgreSQL, Docker, GCP Cloud Run.
* **Links**: [Live Application](https://duo-signa-rose.vercel.app) | [Source Code](https://github.com/vincenzopiconee/DuoSigna)

#### [LLMs in Fabula](https://github.com/vincenzopiconee/LLMsInFabula) — AI-Orchestrated Social Deduction Tabletop Game
* **Overview**: Multiplatform tabletop game (*Lupus in Fabula*) replacing the human moderator with an autonomous Generative AI narrator.
* **Architecture**: Driven by a distributed Finite State Machine (FSM) synchronized in real time across clients through Firebase Realtime Database. Features dynamic context assembly, secret-preserving prompt guardrails, multi-model failover, and client-side Text-to-Speech (TTS) narration via the Web Speech API.
* **Stack**: Flutter, Dart, Firebase (RTDB, Auth, App Check, Hosting), Google Gemini Flash API, Web Speech API.
* **Links**: [Live Web Application](https://llminfabula-1.web.app/) | [Source Code](https://github.com/vincenzopiconee/LLMsInFabula)

---

### 2. Native Apple Platforms & Low-Latency Systems

#### [Trustfall](https://github.com/vincenzopiconee/Trustfall) — Asymmetric Cooperative Multiplayer Game
* **Overview**: Real-time peer-to-peer asymmetric cooperative multiplayer iOS game engineered as a Capstone Project at the Apple Developer Academy.
* **Architecture**: Implements lockstep game state synchronization over Apple GameKit (Game Center). Integrates Agora Real-Time Communication (RTC) SDK for role-restricted push-to-talk voice transmission and AVFoundation for dynamic audio waveform visualization.
* **Stack**: Swift, SwiftUI, GameKit, Agora RTC SDK, AVFoundation.
* **Links**: [Source Code](https://github.com/vincenzopiconee/Trustfall)

#### [Beeep](https://github.com/vincenzopiconee/Beeep) — Serverless P2P Multiplayer iOS Party Game
* **Overview**: Decentralized, serverless local multiplayer game developed natively for iOS at the Apple Developer Academy.
* **Architecture**: Operates over an ad-hoc local mesh network utilizing Apple's MultipeerConnectivity framework (Bonjour discovery over TCP/UDP), enabling zero-internet offline gameplay. Leverages `UIWindowScene` for external dual-screen display management via AirPlay and HDMI.
* **Stack**: Swift, SwiftUI, UIKit, MultipeerConnectivity.
* **Links**: [Source Code](https://github.com/vincenzopiconee/Beeep)

#### [SuperHeroFit](https://github.com/vincenzopiconee/SuperHeroFit) — Gamified Fitness & Health Tracking Application
* **Overview**: Native iOS health gamification application that converts physical movement metrics into virtual character progression.
* **Architecture**: Direct system integration with HealthKit via `HKStatisticsQuery` for background step and distance aggregation. Employs SwiftData for local-first reactive persistence and an optimized layered rendering pipeline for modular 2D avatar customization.
* **Stack**: Swift, SwiftUI, SwiftData, HealthKit, Combine.
* **Links**: [Source Code](https://github.com/vincenzopiconee/SuperHeroFit)

---

### 3. Cross-Platform Applications & Automated Quality Assurance

#### [SeriesTime](https://github.com/vincenzopiconee/SeriesTime) — Cross-Platform Media Tracking & Analytics Platform
* **Overview**: Production-grade TV tracking and analytics application built to commercial product specifications defined in collaboration with **Bending Spoons**.
* **Architecture**: Cross-platform deployment on Flutter web and mobile, integrating the TMDB REST API and Cloud Firestore for real-time bidirectional watchlist synchronization. Features a rigorous automated quality assurance harness consisting of **332 unit and widget tests** with zero static analysis warnings.
* **Stack**: Flutter, Dart, Firebase (Firestore, Auth), REST API (TMDB), Automated Test Harness.
* **Links**: [Live Web Application](https://seriestime-data.web.app) | [Source Code](https://github.com/vincenzopiconee/SeriesTime)

---

### 4. Machine Learning & Computer Vision Research

#### [Pirate Pain Classification](https://github.com/vincenzopiconee/pirate-pain-classification) — Multivariate Time Series Deep Learning Ensemble
* **Overview**: Deep learning pipeline developed for the AN2DL competition at Politecnico di Milano, classifying subjective pain categories from temporal multi-sensor physical measurements.
* **Architecture**: Trained entirely from scratch without pretrained weights. Combines Bidirectional GRU (BiGRU), Bidirectional LSTM with Attention, and 1D Convolutional networks into a heterogeneous voting ensemble. Implemented sliding-window multi-step prediction aggregation and Optuna hyperparameter optimization, achieving a **0.9534 test F1-score**.
* **Stack**: Python, PyTorch, Optuna, Scikit-learn, NumPy.
* **Links**: [Source Code](https://github.com/vincenzopiconee/pirate-pain-classification)

#### [Cancer Image Classification](https://github.com/vincenzopiconee/cancer-image-classification) — Breast Cancer Histopathology Subtyping via Vision Transformers
* **Overview**: Whole Slide Image (WSI) diagnostic subtyping model addressing extreme spatial imbalance and tissue sparsity (~1.9% average diagnostic region).
* **Architecture**: Engineered an instance cropping pipeline based on spatial clustering (yielding a 4x dataset expansion) and fine-tuned domain-specific Vision Transformers (UNI, Phikon). Utilized Grad-CAM for visual interpretability and pathological feature localization.
* **Stack**: Python, PyTorch, Vision Transformers, OpenCV, Grad-CAM.
* **Links**: [Source Code](https://github.com/vincenzopiconee/cancer-image-classification)

---

### 5. Enterprise Software Engineering & Object-Oriented Architecture

#### [Artist Management System](https://github.com/vincenzopiconee/artist-management-system) — Agency Booking & Auditing Desktop System
* **Overview**: Desktop information system engineered under the Unified Process for musical artist booking agency operations.
* **Architecture**: Strictly implements the Boundary-Control-Entity (BCE) architectural pattern and the Data Access Object (DAO) pattern. Implements transactional persistence via raw JDBC against a relational MySQL schema, singleton controllers for domain rules, automated event summons lifecycles, monthly financial auditing, and extensive JUnit structural and functional test suites (Boundary Value Analysis, Cyclomatic Complexity).
* **Stack**: Java, Java Swing, MySQL, JDBC, DAO Pattern, BCE Architecture, JUnit, Maven.
* **Links**: [Source Code](https://github.com/vincenzopiconee/artist-management-system)

---

## Contact & Links

* **LinkedIn**: [linkedin.com/in/vincenzo-piconee](https://www.linkedin.com/in/vincenzo-piconee)
* **GitHub**: [github.com/vincenzopiconee](https://github.com/vincenzopiconee)

* **Locations**: Madrid, Spain & Milan, Italy
