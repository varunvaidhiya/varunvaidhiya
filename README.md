<!-- Typing SVG Header -->
<p align="center">
  <a href="https://github.com/DenverCoder1/readme-typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&duration=4000&pause=1000&color=2E9EF7&center=true&vCenter=true&width=800&lines=Hi+%F0%9F%91%8B%2C+I'm+Varun+Vaidhiya;Robot+Learning+%26+AI+Inference+Engineer;Robot+learning+data+%26+training+platforms;GPU+%2F+edge-GPU+inference+optimisation" alt="Typing SVG" />
  </a>
</p>

<h3 align="center">Robot Learning & AI Inference Engineer · Robot-learning data & training platforms · GPU / edge-GPU inference optimisation</h3>

<p align="center">
  Building <a href="https://github.com/ohho-robotics/OmniBot"><b>OmniBot</b></a>, an open-source mobile manipulator, at <a href="https://ohho-robotics.com">Ohho Robotics</a>
</p>

<p align="center">
  Open to robot learning, AI engineering and ML/AI performance roles
</p>

<p align="center">
  <a href="https://varunvaidhiya.com">Website</a> ·
  <a href="https://www.linkedin.com/in/varunvaidhiya">LinkedIn</a> ·
  <a href="https://x.com/VarunVaidhiya">X</a> ·
  <a href="https://varunvaidhiya.substack.com">Substack</a> ·
  <a href="https://www.youtube.com/@varun.vaidhiya">YouTube</a>
</p>

---

## 👨‍💻 About Me

I build the **software platform that makes robot learning work** (teleoperation data collection, episodic data pipelines, training and policy-serving infrastructure) and I **make AI models run fast on real compute**: GPU and edge-GPU inference, quantisation and model performance optimisation.

- 🔭 Working on: **OhhO Robotics** (Founder): the open-source software stack for robot learning on mobile manipulators. Ohho OS is open source (Apache-2.0).
- 🤖 **Robot learning platform**
  - **Teleoperation data collection**: VR / mobile teleop pipelines for recording demonstrations.
  - **Data pipelines**: LeRobot-format episodic datasets, shared camera schemas, bag conversion and episode quality filtering.
  - **Training & serving**: imitation-learning training infrastructure and a ROS 2 policy-inference node that runs trained policies on the robot.
- ⚡ **AI optimisation on compute**
  - **GPU / edge-GPU inference**: TensorRT FP16 engine for visuomotor-policy vision encoders (OmniBotPro).
  - **Model compression & benchmarking**: SAM 2 post-training quantisation and structured pruning, benchmarked against SegFormer on an RTX 4070 Mobile ([SAM2forAV](https://github.com/varunvaidhiya/SAM2forAV)).
  - **CUDA & ARM**: [libfreenect2 fork](https://github.com/varunvaidhiya/libfreenect2) with CUDA 13.0 fixes and Raspberry Pi 5 / ARM64 support; CUDA programming practice; performance trace analysis (Perfetto).
- ⚙️ Core Stack: PyTorch, LeRobot, ROS 2, TensorRT, ONNX, CUDA, Docker, Python, C++.
- 💡 Interests: efficient inference for robot policies and foundation models (including VLAs) on edge GPUs.
- 📫 Email: varun@ohho-robotics.com

---

## 🔨 Recent Work

- [OmniBot #10](https://github.com/ohho-robotics/OmniBot/pull/10): arm emergency stop now drops servo torque; the driver holds position on stale commands and clamps joint limits and per-cycle steps.
- [OmniBot #13](https://github.com/ohho-robotics/OmniBot/pull/13): the LeRobot policy node skips missing or black camera frames, drops stale inference, and clamps arm deltas.
- [OmniBot #12](https://github.com/ohho-robotics/OmniBot/pull/12): one shared wrist + bird's-eye camera schema across recording, validation, bag conversion and the policy.
- [OmniBot #14](https://github.com/ohho-robotics/OmniBot/pull/14): episode quality filter CLI for LeRobot datasets that rejects frozen video, camera timestamp skew, joint jumps and too-short episodes.
- [OhhO-VR #5](https://github.com/ohho-robotics/OhhO-VR/pull/5): GameCI workflow that runs the Unity edit-mode test suite in CI.
- [ohho-os 1.1.2](https://pypi.org/project/ohho-os/1.1.2/): released to PyPI through a tag-triggered trusted-publishing workflow with install smoke tests on Ubuntu and macOS.

---

## 🛠️ Technology Stack

### Robot Learning & Model Training
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/HuggingFace-F9AB00?style=for-the-badge&logo=huggingface&logoColor=white)
![LeRobot](https://img.shields.io/badge/LeRobot-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Imitation Learning](https://img.shields.io/badge/Imitation_Learning-FF6F00?style=for-the-badge)
![Reinforcement Learning](https://img.shields.io/badge/Reinforcement_Learning-282C34?style=for-the-badge&logo=openai&logoColor=white)

### GPU & Edge Inference Optimisation
![NVIDIA CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![Quantisation](https://img.shields.io/badge/Quantisation_%26_Pruning-4B0082?style=for-the-badge)
![Arm](https://img.shields.io/badge/Arm_%2F_NEON-0091BD?style=for-the-badge&logo=arm&logoColor=white)

### Robotics Software Platform
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![NVIDIA Isaac](https://img.shields.io/badge/Isaac_Sim-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-FF8C00?style=for-the-badge)

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### Data & Infrastructure
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Data Pipelines](https://img.shields.io/badge/Data_Pipelines-00599C?style=for-the-badge)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 📊 GitHub Statistics

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=varunvaidhiya&show_icons=true&theme=algolia&include_all_commits=true&count_private=true" alt="GitHub Stats" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=varunvaidhiya&layout=compact&langs_count=8&theme=algolia" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=varunvaidhiya&theme=algolia" alt="GitHub Streak" />
</p>

<p align="center">
<!-- commits.sh:profile:start -->
<a href="https://commits.sh/varunvaidhiya">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://commits.sh/api/badge?handle=varunvaidhiya&amp;style=card&amp;theme=light&amp;v=52w1" />
    <img src="https://commits.sh/api/badge?handle=varunvaidhiya&amp;style=card&amp;theme=dark&amp;v=52w1" alt="varunvaidhiya's public GitHub activity on commits.sh" width="480" />
  </picture>
</a>
<!-- commits.sh:profile:end -->
</p>

---

## 🎯 Key Focus Areas

```python
class VarunVaidhiya:
    def __init__(self):
        self.role = "Robot Learning & AI Inference Engineer"
        self.expertise = [
            "Robot learning platforms: teleop data collection to trained policy",
            "Episodic data pipelines & dataset quality (LeRobot format)",
            "Training & policy-serving infrastructure",
            "GPU / edge-GPU inference (TensorRT, ONNX, CUDA)",
            "Model optimisation: quantisation, pruning, benchmarking",
        ]
        self.current_projects = [
            "OhhO Robotics: open-source robot learning software stack",
            "VR / mobile teleoperation data pipelines",
            "Accelerated on-robot policy inference",
        ]
        self.looking_for = {
            "opportunities": "Robot learning, AI engineering & ML/AI performance roles",
            "collaborations": "Robot learning infrastructure, efficient edge inference",
        }

    def say_hi(self):
        print("Let's make robot learning scale and AI run fast!")
```

---

## 📫 Connect With Me

<p align="center">
  <a href="mailto:varun@ohho-robotics.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/varunvaidhiya">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://varunvaidhiya.com">
    <img src="https://img.shields.io/badge/Website-0E75B6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" />
  </a>
  <a href="https://www.linkedin.com/in/varunvaidhiya">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn" />
  </a>
  <a href="https://x.com/VarunVaidhiya">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" />
  </a>
  <a href="https://varunvaidhiya.substack.com">
    <img src="https://img.shields.io/badge/Substack-FF6719?style=for-the-badge&logo=substack&logoColor=white" alt="Substack" />
  </a>
  <a href="https://www.youtube.com/@varun.vaidhiya">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
  </a>
</p>

---

## 🏷️ Interests & Keywords

`#RobotLearning` `#ImitationLearning` `#Teleoperation` `#DataEngineering` `#MLInfrastructure` `#GPUInference` `#EdgeAI` `#TensorRT` `#ModelOptimisation` `#ROS2` `#OhhORobotics` `#PhysicalAI`

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=varunvaidhiya&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views" />
  <br/>
  <em>🌟 Open to collaborations, research opportunities, and interesting projects in AI & Robotics!</em>
</p>

---

<p align="center">
  <sub>🛠️ From <a href="https://github.com/varunvaidhiya">varunvaidhiya</a> | Last updated: 2026</sub>
</p>
