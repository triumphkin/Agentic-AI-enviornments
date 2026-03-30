# 🟩🟨⬜ AI Wordle: A PyTorch-Powered Word Game
**Built for the Meta PyTorch Hackathon by Scaler School of Technology**

[![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)](https://pytorch.org/)
[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)

## 💡 The Vision
A modern, deep-learning-adjacent take on the classic daily word game, Wordle. This project bridges the gap between traditional game logic and advanced tensor operations, demonstrating how PyTorch can be utilized beyond standard classification tasks to power interactive text-based environments and intelligent solvers. 

## 🛠️ Tech Stack
* **Core Framework:** PyTorch 
* **Language:** Python 3.x
* **Data Handling:** NumPy, Pandas (for vocabulary processing)
* **Interface:** [e.g., CLI / Streamlit / Flask - *Update as needed*]

## ✨ Key Features
* **Tensor-Based Game Engine:** Core game logic (word validation, color-coding feedback) is optimized using PyTorch tensor operations for lightning-fast state evaluations.
* **Intelligent Vocabulary Processing:** Efficient loading and filtering of the 5-letter word dictionary using vectorized constraints.
* **[Optional AI Feature]: Auto-Solver / Hint Engine:** [If you built an AI solver, mention it here! e.g., "An algorithmic solver that calculates information entropy to suggest the mathematically optimal next guess."]
* **Scalable Architecture:** Built with a modular pipeline, making it easy to plug in reinforcement learning agents or sequence models in the future.

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone [https://github.com/yourusername/pytorch-wordle.git](https://github.com/yourusername/pytorch-wordle.git)
   cd pytorch-wordle


   🧠 What I Learned

Building this project under the hackathon time constraints was an incredible experience. Key takeaways include:

    Practical Tensor Manipulation: Translating standard string-matching logic into PyTorch tensor operations forced me to think differently about data structures, optimizing for matrix operations rather than simple loops.

    Applying Deep Learning Concepts: Moving beyond theoretical coursework and assignments into a fully interactive project. Applying concepts from sequence modeling and neural networks to a real-time character-based environment solidified my understanding of how data flows through a pipeline.

    Debugging and Edge Cases: Handling edge cases—like words with repeating letters and ensuring the green/yellow/gray feedback matches exactly with standard Wordle rules—required precise algorithmic thinking.

    Rapid Iteration: Scoping the project down to a robust MVP, ensuring the core PyTorch mechanics worked flawlessly before adding extra features.

🔮 Future Scope

    Reinforcement Learning Agent: Training a Deep Q-Network (DQN) in PyTorch to play the game autonomously and learn the optimal starting words.

    Sequence Models: Integrating an LSTM or Transformer model to predict the probability of hidden words based on letter frequencies and user guesses.

    Interactive Web UI: Wrapping the PyTorch backend in a responsive frontend (like Streamlit or React) for a better user experience.

🤝 Acknowledgments

    Meta & Scaler School of Technology: For hosting the hackathon and providing the platform to build and innovate.
