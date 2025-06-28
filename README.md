# ISPM-Heat-Treat-Inspection-System-Automated-Pallet-Compliance-Verification
Project Overview
ISPM-Heat-Treat-Inspection-System-Automated-Pallet-Compliance-Verification is a real-time, vision-based inspection system for pallet production, developed to verify ISPM 15 heat treatment stamps and stencils for regulatory compliance. The system automates print quality checks, alignment verification, and pallet classification, ensuring international standards are met at production speed.


# Images
![3HT-inspection-software3](https://github.com/user-attachments/assets/72e7fc31-2c7d-4096-b121-3f0cd6d862f6)

![HT-inspection-software](https://github.com/user-attachments/assets/cb52d6b6-d904-4613-81a2-7a05a7d31ceb)


![HT-inspection-software2](https://github.com/user-attachments/assets/a841919e-5103-46fa-9af7-ea31cc38f043)

Key Features
✅ Real-time HT stamp and ISPM stencil detection using YOLOv8

✅ Alignment and dimensional verification within ±1mm tolerance

✅ Multi-camera Basler GigE setup with auto-recovery

✅ Live classification: Compliant / Non-compliant pallets

✅ Real-time MQTT alerts for operators

✅ AWS cloud integration: PostgreSQL, S3, FastAPI, Streamlit dashboards

✅ Local SQLite caching for network resilience

✅ Automated audit reporting and database cross-verification

Technologies Used
Python 3, OpenCV, YOLOv8, MobileNet, PyTorch

Basler GigE cameras (pypylon)

FastAPI, PostgreSQL, SQLite, Boto3, MQTT

AWS S3 for image storage

Streamlit for real-time quality dashboards

Impact
📦 Reduced manual inspection by 80%

⚙️ Increased production throughput by 25%

✅ Achieved 98% detection accuracy

📊 Enabled real-time, multi-site cloud dashboards

🗂️ Reduced audit reporting time by 70%

Challenges Solved
Tackled print variation with augmented training data

Achieved sub-100ms detection latency using CUDA and parallel processing

Ensured cloud reliability with offline caching and resilient APIs

My Role
As Lead Vision System Developer & Integration Engineer, I:

Designed and deployed the full vision system

Trained custom YOLOv8 models for pallet print detection

Integrated cameras, PLCs, cloud APIs, and MQTT workflows

Delivered a fully production-ready, fault-tolerant solution

Project Status
🚀 Tested, ready to run on production lines.
