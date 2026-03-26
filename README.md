## Privion Rehab – Adaptive Recovery Intelligence

### Overview

Privion Rehab is an Android-based recovery support application that uses on-device AI to analyse subtle body signals during rehabilitation and training. It helps users track pain, fatigue, and movement issues, and converts them into actionable insights to support safer, more personalised recovery.

---

### Key Features

* Signal logging (pain, fatigue, instability)
* AI-driven pattern detection across sessions
* Real-time feedback and recovery insights
* Clinician summary mode for structured reports
* Local data storage for session history

---

### Tech Stack

* Android Studio (Kotlin, Jetpack Compose)
* Llama 3.2 (on-device inference)
* Google AI Edge SDK (or similar)
* Room Database (local storage)

---

### Architecture

The system follows a simple pipeline:

User → Android UI → ViewModel → Local Database → On-device Llama AI → Insights → UI

The AI engine processes structured user signals and historical data to generate real-time feedback and summaries.

---

### AI Integration

Llama 3.2 is used on-device to:

* classify user-reported signals
* detect patterns across sessions
* generate concise feedback and summaries

On-device inference ensures privacy, low latency, and offline functionality.

---

### Setup Instructions

1. Clone the repository
2. Open in Android Studio
3. Sync Gradle files
4. Run on emulator or physical device

---

### Project Structure

* `/app` – Android application source code
* `/Task 4.0` – Final report, architecture diagram, and supporting files
* `README.md` – Project documentation

---

### Notes

This project focuses on system design and AI integration. Some features may be represented as prototypes or simplified implementations.


