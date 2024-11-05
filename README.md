# 🌟 Welcome to Project Varuna! 🌟

Hi there! 
I'm **Ajinkya Joglekar**, a passionate Ph.D. candidate at the prestigious **Clemson University's International Center for Automotive Research (ICAR)**, nestled in the vibrant city of Greenville, SC. I'm thrilled to share my journey and research in the cutting-edge realm of on-road and off-road Uncrewed Ground Vehicle systems (UGVs). 🚗 :robot:

## 🚀 About Project Varuna:
Project Varuna is an innovative framework grounded in my research on Koopman Operator Theory. This platform distills the insights and innovations from my work into a standalone package, empowering users to build explainable, data-driven models with just a few clicks, making advanced autonomy accessible to all. 
Find out more at:
[Project Varuna](https://www.project-varuna.com/)

🔍 **Key Highlights:**

- **Multi-Model Parameterized Koopman (MMPK) approach:** Captures vehicle dynamics using a curvature-parameterized family of Koopman models, ensuring coverage across the entire operational envelope. 
- **Novel Reachability-Based Planners:** Sample a set of feasible trajectories to bridge Sim2Real gaps and mitigate terrain perturbations. 
- **Linear Feedback Controller in Lifted Space:** Enables robust path-tracking in real-time, even on systems with limited computational resources. 
- **Open-Source Packages & User-Friendly GUI:** No complex setup or dependencies! Simply select modeling, planning, and control parameters through the GUI, and you're ready to go! 
- **Cross-Compatibility:** Works with multiple simulators (e.g. AutoDRIVE Ecosystem, Nvidia Isaac Sim) and hardware platforms, from 1/10th scale (F1Tenth) to mid-scale (Hunter SE) and full-scale vehicles.
  
By blending these pipelines, Project-Varuna aims to enhance the intelligence and decision-making capabilities of autonomous vehicles, pushing their operational envelope even further in diverse and challenging conditions.


## Usage Guidelines

### Data Processing

To get started with data-driven modeling using Project Varuna, datasets need to be in a compatible format. For release version v1.0, training and testing datasets can be prepared in one of the following formats:

- **Project Varuna Custom Format**:  
  For mid-scale Hunter-SE data, a pre-curated dataset and the required structure can be found in this repository:  
  [Project Varuna Datasets](https://github.com/project-varuna/Project-Varuna-Datasets).

- **AutoDRIVE Format**:  
  This format extends the AutoDRIVE dataset structure, which you can find here:  
  [AutoDRIVE Hunter-SE Dataset](https://github.com/Tinker-Twins/AutoDRIVE-Hunter-SE-Dataset).  
  In this format, all runs have been compiled and preprocessed to include throttle-to-velocity mapping and smoothed data. The processed dataset is available at:  
  [AutoDRIVE Processed Datasets](https://github.com/project-varuna/AutoDRIVE-Processed-Datasets).

### Using Pre-trained Models (Optional)

If you'd like to use pre-trained models instead of training your own, models for the 1/5th scale Hunter SE platform are available here:  
[Hunter-SE MMPK Models](https://github.com/project-varuna/Hunter-SE-MMPK-Models.git).

### Modeling and Deployment with Project Varuna Software Kit

Once your datasets are set up in one of the compatible formats, you can proceed with the Project Varuna software kit:

1. **Model Dynamics**: Use the GUI to model dynamics, set motion planner parameters, and configure the linear Model Predictive Controller.
2. **Select Reference Trajectory**: Choose the reference trajectory for your deployment.
3. **Start Deployment**: You're all set! Simply initiate the process to begin.

For detailed setup instructions and additional package information, visit:  
[Project Varuna Autonomy Package](https://github.com/project-varuna/Project-Varuna-Autonomy-Package).



## 🤝 Collaboration and Contributions:
I firmly believe in the power of **teamwork**. I'm always open to collaborating with like-minded individuals and teams to tackle autonomy's most challenging problems. Together, we can pool our expertise and create groundbreaking solutions that shape the future of autonomous systems.


Feel free to explore my Project Varuna, provide feedback, or suggest collaborations. Together, we can push the boundaries of data-driven modeling and controls in challenging operating spaces and contribute to a safer, smarter, and more efficient UGVs.
Thank you for visiting my repository—I'm excited to embark on this journey of innovation and discovery with you! ✨

---

📫 **Let's Connect:**

- **Email:** [ajinkya.project-varuna@gmail.com](mailto:ajinkya.project-varuna@gmail.com)
- **ResearchGate:** [Ajinkya Joglekar](https://www.researchgate.net/profile/Ajinkya-Joglekar)
- **LinkedIn:** [Ajinkya Joglekar](https://www.linkedin.com/in/ajinkyajoglekar/)
