#  🚗 Collision-Warning-System ( Dashcam-Based AI ALert)


This is a AI projects that **aims to warn drivers about potential collisions using dashcam video analysis.**

### Objective:
To build a real-time collision alert system that analyzes dashcam footage and gives warnings like:
- ⚠️"Car CLose"
- ⚠️"Truck Close"
- ⚠️"Bus Close"
- ⚠️"Warning: Pedestrain/Bicycle"

  
These alerts help drivers **stay cautious in complex traffic conditions.**

---

### Designed For:
-Dashcam mounted on car windshieled
-Works even when **car bonnet is partially visible**
-Tested in **rainy weather conditions** to improve robustness


---

###Tech Stack:
-**Python**
-**OpenCV**
-**YOLOv5(pretrained model)** for object detection
-Real-time **frame wise video analysis**

---

### Current Features:
- Detect **vehicles and humans** from dashcam video
- Warns based on **object type and proximity**
- Displays alerts dynamically on the video frame
- Capable of running in **moderate weather interference** (e.g rain)
- Supports videos with **bonnet partially in frame**

- -

### Work in Progess:
- Improving **false-positive filtering** using confidence level threshold and bounding box logic
- Adding **distance estimation** for more accurate warnings
- Planning to integrate **audio alerts**
- UI/UX polish and documentation underway

---

### Note:
this project is being improved regularly by experiementing with differentdetection strategiesand edge cases.

---
## Developer
**Snehal DUbey**
B.Tech CSE student, RTU KOta
Learning AI/ML through hands-on projects like this

---


### Want to Help / Collaborate?
If you are into Computer Vision, YOLO, Or AI prjoects like this, feel free to raise issues or suggest improvements. Let's make safe driving smarter together!

