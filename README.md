<!-- HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&height=170&color=0:89f7fe,100:66a6ff&section=header&text=Taegi%20You&fontSize=42&fontColor=ffffff"/>

<div align="center">

### 🤖 Humanoid Robot Learning · RL Motion Imitation · Sim-to-Real

Training reinforcement-learning policies for humanoid robots and taking them from simulation to real hardware.

🏫 Seoul National University of Science and Technology<br/>
🦾 Robotics AI Intern @ ROBOTIS

📫 utaek21021@gmail.com · 📝 [velog](https://velog.io/@ryutaegi/posts)

</div>

---

## 🧭 Focus

- **Motion imitation RL** — teaching a full-size humanoid dynamic whole-body skills (cartwheel, kip-up, jump-on-box, taekwondo forms) from human reference motion
- **Sim-to-real transfer** — actuator modeling, system identification and domain randomization so that policies survive real motors, sensors and latency
- **Human motion → robot** — video-based human pose capture and retargeting into physically feasible robot reference motion

---

## 🛠 Experience

**Robotics AI Intern · ROBOTIS** — humanoid RL & sim-to-real

- Designed rewards, terminations and curricula for highly dynamic humanoid skills; diagnosed and fixed reward exploits by analyzing rollouts and per-term logs
- Built measured-torque actuator models with randomized control delay; ran system identification of joint dynamics against real-robot logs
- Analyzed torque saturation and real-vs-sim gaps from robot logs (rosbag) and fed the findings back into training
- Trained teacher–student (distillation) policies, adversarial motion priors (AMP) and depth-camera student policies
- Validated policies across simulators (Isaac Lab, Newton, MuJoCo/mjlab) with sim-to-sim checks before hardware
- Exported policies (ONNX) into the onboard C++/ROS 2 runtime: observation ports, smooth policy-switch blending, controller mode wiring
- Built a mocap → robot pipeline: video human mesh recovery, floor-drift correction, kinematic & physics-based retargeting
- Explored whole-body control + VLA integration and real-time camera-driven upper-body imitation on an embedded GPU (TensorRT)

---

## 🧰 Tech Stack

**Robot Learning**<br/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/PPO%20(rsl__rl)-555555?style=flat-square"/>
<img src="https://img.shields.io/badge/Isaac%20Lab-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
<img src="https://img.shields.io/badge/Newton-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
<img src="https://img.shields.io/badge/MuJoCo%20%2F%20mjlab-1F6FEB?style=flat-square"/>
<img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white"/>

**Deployment**<br/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
<img src="https://img.shields.io/badge/ROS%202-22314E?style=flat-square&logo=ros&logoColor=white"/>
<img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white"/>
<img src="https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>

**Motion Data**<br/>
<img src="https://img.shields.io/badge/Human%20Mesh%20Recovery-555555?style=flat-square"/>
<img src="https://img.shields.io/badge/SMPL-555555?style=flat-square"/>
<img src="https://img.shields.io/badge/Retargeting-555555?style=flat-square"/>

**Also** · Embedded & Web<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black"/>
<img src="https://img.shields.io/badge/Raspberry%20Pi-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white"/>

---

## 📊 GitHub

<div align="center">
<img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ryutaegi&theme=github"/>
</div>

<!-- FOOTER -->
<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:89f7fe,100:66a6ff&section=footer"/>
