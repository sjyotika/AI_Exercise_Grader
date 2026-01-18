🏋️ AI Exercise Grader – Real-Time Posture & Form Evaluation

📌 Overview

This project is an AI-based virtual fitness trainer that uses computer vision and pose estimation to analyze exercise posture in real time and provide instant feedback on form quality.

Unlike basic fitness trackers that only count repetitions, this system focuses on exercise correctness, helping users reduce injury risk and improve workout effectiveness while exercising at home.

🎯 Problem Statement

Many people exercise without professional supervision, leading to:

Incorrect posture

Ineffective workouts

High risk of injury

Most online workout videos and basic fitness apps do not provide real-time corrective feedback, which is critical for safe training.

💡 Proposed Solution

This system acts as a virtual personal trainer by:

Detecting human body pose using a webcam

Calculating joint angles (knees, hips, etc.)

Applying biomechanical rules to evaluate posture

Providing real-time visual (and optional voice) feedback

The solution is lightweight, explainable, and runs entirely on CPU, making it accessible on standard laptops.

⭐ Key Features

✅ Real-time pose detection using webcam

✅ Exercise form evaluation (currently supports squats)

✅ Joint-angle based posture analysis

✅ Instant corrective feedback

✅ Optional voice coaching

✅ No dataset or model training required

✅ Runs on CPU (no GPU needed)

🆕 Innovation & Uniqueness

Compared to existing exercise counters, this project adds:

Form quality grading, not just repetition counting

Explainable feedback based on joint angles

Rule-based posture correction similar to real trainers

Beginner-friendly, transparent logic instead of black-box models

This transforms the system from a simple tracker into an intelligent coaching assistant.

🛠️ Tech Stack

Programming Language: Python

Pose Estimation: MediaPipe Pose

Video Processing: OpenCV

Numerical Computation: NumPy

Voice Feedback (Optional): pyttsx3

🧠 System Workflow
Webcam Input
   ↓
Pose Estimation (MediaPipe)
   ↓
Joint Angle Calculation
   ↓
Rule-Based Exercise Evaluation
   ↓
Real-Time Feedback (Text / Voice)

🧪 How It Works (Conceptually)

Webcam captures live video

MediaPipe extracts body landmarks

Joint angles (hip, knee, ankle) are calculated

Angles are compared against predefined thresholds

Feedback is displayed based on posture correctness

No deep learning training is required — the intelligence lies in pose interpretation and rule-based reasoning.

▶️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/sjyotika/ai-exercise-grader.git
cd ai-exercise-grader

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Application
python main.py


📷 Make sure your webcam is enabled.

🧪 Testing & Validation

The system was tested using:

Correct squat posture

Partial squats

Incorrect back alignment

Feedback changes dynamically based on posture, demonstrating real-time responsiveness and robustness.

⚠️ Limitations

Currently supports a limited set of exercises

Performance depends on camera angle and lighting

Not a replacement for professional medical advice

🚀 Future Improvements

Support for more exercises (push-ups, lunges, planks)

Personalized calibration for different body types

Exercise scoring & progress tracking

Mobile application integration

Improved fatigue detection

🌍 Real-World Impact

Enables safe home workouts

Reduces injury risk

Provides affordable access to guided fitness

Useful in fitness coaching, rehabilitation, and tele-health

📌 Conclusion

This project demonstrates how computer vision and AI can be used responsibly and practically to solve real-world health and fitness problems. It highlights the power of explainable, lightweight AI systems that prioritize usability and impact.

🙋 Author

Jyotika Satav
(AI / Computer Vision Enthusiast)
