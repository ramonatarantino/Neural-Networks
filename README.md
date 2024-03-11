# Neural-Networks
## PEFT Methods Python Implementations README

### Overview
This repository contains a collection of Python notebooks demonstrating various Parameter-Efficient Fine-Tuning (PEFT) methods, including LoRA, adapters, and soft prompting. These methods are applied across different models and tasks, showcasing their versatility and efficiency in enhancing model performance with minimal parameter updates.

## Notebooks Description
1. **EfficientNet B0 + LoRA** (efficient-net.b0 + lora.ipynb)
This notebook explores the integration of LoRA (Low-Rank Adaptation) with EfficientNet B0, focusing on fine-tuning the model in a parameter-efficient manner. LoRA introduces low-rank matrices to the network, enabling efficient learning of task-specific adaptations without significant increases in the model's parameter count.

2. **GPT-2 + LoRA** (Gpt2-Lora.ipynb)
In this notebook, LoRA is applied to the GPT-2 model to demonstrate advanced transfer learning capabilities. The implementation highlights how LoRA can be leveraged to fine-tune language models effectively, enhancing their adaptability to specific tasks while maintaining a constrained parameter budget.

3. **Model Ratatouille** (model_ratatouille.ipynb)
This notebook delves into model merging and combination techniques, showcasing a "model ratatouille" approach. It illustrates how different model representations can be merged or combined, potentially using techniques like relative representations, to create a more robust and versatile final model.

4. **ResNet + Adapters** (resnet-adapters-lora.ipynb)
The focus here is on integrating adapters with ResNet, complemented by LoRA adjustments. This notebook provides insights into how adapters can be inserted into a well-known architecture like ResNet to fine-tune it for specific tasks, demonstrating the flexibility and efficiency of adapters in model fine-tuning.

5. **Saliency Maps** (Saliency-maps.ipynb)
While not directly related to PEFT, this notebook offers an exploration of saliency maps for model interpretability. It provides a hands-on demonstration of how saliency maps can be used to interpret and understand the focus and decision-making process of neural networks, contributing to the broader understanding of model behaviors.

## Getting Started
To run these notebooks, ensure you have a Python environment set up with the necessary libraries and dependencies installed. Each notebook contains specific setup instructions and requirements for the models and methods demonstrated.

### Contributing
Contributions to this repository are welcome! Whether it's adding new PEFT method implementations, enhancing the existing notebooks, or providing additional documentation, your input is valuable. Please follow the standard pull request process to submit your contributions.
