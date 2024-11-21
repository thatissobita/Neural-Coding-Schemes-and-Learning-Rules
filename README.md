# Neural Coding Schemes and Learning Rules  

Welcome to the **Neural Coding Schemes and Learning Rules** repository! This project explores neural encoding schemes for visual tasks and implements biologically plausible learning rules to model synaptic plasticity in spiking neural networks. Using the `pymonntorch` framework, the repository includes implementations of Poisson encoding, Time-To-First-Spike (TTFS) encoding, and numerical value encoding, as well as learning mechanisms like Spike-Timing Dependent Plasticity (STDP) and Reward-Modulated STDP (R-STDP).  

---

## Features  

- **Neural encoding schemes:**  
  - Poisson encoding: Encodes visual data into spike trains based on Poisson distributions.  
  - Time-To-First-Spike (TTFS): Encodes pixel intensities into spike times.  
  - Numerical values encoding: Maps numerical data directly into spiking patterns.  

- **Learning and synaptic plasticity:**  
  - STDP: Implements spike-timing dependent plasticity to adjust synaptic weights based on timing relationships.  
  - R-STDP: Models reward-modulated STDP to include reinforcement learning elements in spiking neural networks.  

- **Interactive notebook:** A single Jupyter notebook (`Neural-Coding-and-Learning-Rules.ipynb`) consolidates the implementation and analysis.  

- **Visualization resources:** Pre-generated plots and figures included in the `resources/` folder.  

- **Detailed report:** A comprehensive `report.pdf` providing theoretical background, results, and discussions.  

---

## Installation  

1. Clone this repository:  
   ```bash  
   git clone https://github.com/yourusername/Neural-Coding-and-Learning-Rules.git  
   cd Neural-Coding-and-Learning-Rules  
   ```  

2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

   **Note:** Ensure you have Python 3.8 or higher installed.  

---

## Usage  

### Running the Jupyter Notebook  

1. Open the Jupyter notebook:  
   ```bash  
   jupyter notebook Neural-Coding-and-Learning-Rules.ipynb  
   ```  

2. Follow the step-by-step implementation for encoding schemes and learning rules.  
3. Generate plots and analyze results directly within the notebook.  

---

## Directory Structure  

```plaintext  
Neural-Coding-and-Learning-Rules/  
│  
├── Neural-Coding-and-Learning-Rules.ipynb  # Jupyter notebook containing all implementations and analysis  
│  
├── report.pdf                              # Detailed report including results and analysis  
│  
├── resources/                              # Folder for visualization resources  
│   ├── poisson_encoding.png                # Visualization of Poisson encoding  
│   ├── ttfs_encoding.png                   # Visualization of Time-To-First-Spike encoding  
│   ├── numerical_encoding.png              # Visualization of numerical encoding  
│   ├── stdp_learning.png                   # Visualization of STDP learning  
│   ├── rstdp_learning.png                  # Visualization of Reward-Modulated STDP learning  
│  
├── requirements.txt                        # Python dependencies  
├── LICENSE                                 # License information  
├── README.md                               # Project documentation  
└── .gitignore                              # Git ignored files  
```  

---

## Results  

The `resources/` folder contains pre-generated plots and visualizations, including:  
- Spike trains generated using Poisson and TTFS encoding schemes.  
- Numerical encoding patterns for spiking networks.  
- Weight changes and learning curves for STDP and R-STDP.  
- Comparative analysis of learning rules in network performance.  

Refer to the `report.pdf` for a detailed discussion of these results.  

---

## Dependencies  

- Python 3.8+  
- `pymonntorch`
- `pytorch`
- `numpy`  
- `matplotlib`  

Install all dependencies using the provided `requirements.txt` file.  

---

## Contributing  

Contributions are welcome! To contribute:  
1. Fork the repository.  
2. Create a feature branch.  
3. Submit a pull request with your changes.  

For major changes, please open an issue to discuss your ideas.  

---

## Acknowledgements  

This project leverages the [pymonntorch](https://github.com/cnrl/PymoNNtorch) framework for spiking neural network simulations.  

Happy experimenting with neural coding schemes and learning rules!
