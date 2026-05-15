# AI Core Mechanics: From Scratch to PyTorch

##  Objective
This repository documents my journey of learning AI Engineering from first principles. Instead of just calling high-level APIs, I built the underlying mathematics of a neural network to truly understand backpropagation before translating it into industry-standard PyTorch.

##  What's Inside
* **Custom Autograd Engine:** A from-scratch automatic differentiation engine written in pure Python, implementing the Chain Rule for scalar values.
* **PyTorch Translation:** The exact same mathematical graph and training loop implemented using `torch.Tensor` and `backward()` to demonstrate the 1:1 relationship between the mathematical theory and modern AI frameworks.

##  Key Learnings
* **Calculus to Code:** Implemented the Chain Rule programmatically using Python dunder methods (`__add__`, `__mul__`).
* **Topological Sort:** Built the sorting algorithm required to ensure gradients flow backward in the correct sequence.
* **Framework Deconstruction:** Demystified PyTorch by proving that its complex autograd system runs the exact same logic as my custom Python engine.

##  How to Run
1. Clone the repository to your local machine.
2. Open the `.ipynb` file in Jupyter Notebook or Google Colab.
3. Run the cells sequentially to watch the custom engine and PyTorch output the exact same gradients.
