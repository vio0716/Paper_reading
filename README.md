# Figure–Equation–Code Aligned Paper Reading Prompt

A reusable prompt for deep reading of research papers, designed to align **figures**, **equations**, **module logic**, and **code** (when available).

## Features

- **Faithful to the text**: grounded in the original paper rather than free-form summarization  
- **Figure–equation alignment**: explains modules by binding formulas to architecture diagrams  
- **Module-level deep dive**: focuses on what each module does, why it exists, and how it connects to the full pipeline  
- **Code-assisted interpretation**: incorporates source code only when code is available  
- **Reproduction-friendly**: useful for implementation, related work writing, and method comparison  

## Best Use Cases

- Computer Vision papers  
- Deep Learning methods  
- Image restoration / enhancement / dehazing / denoising / diffusion papers  
- Reproduction-oriented reading  
- Related work writing  
- Module-by-module paper analysis  

## How to Use

1. Upload a paper PDF to your LLM tool.
2. Open the full prompt here: [prompt.md](./prompt.md)
3. Paste the prompt into the chat.
4. Optionally provide:
   - source code
   - supplementary material
   - implementation notes
5. Ask the model to analyze the paper section by section or module by module.

## Repository Structure

- [`README.md`](./README.md): project overview  
- [`prompt.md`](./prompt.md): full reusable prompt  

## Notes

- The prompt is designed to be **strictly grounded in the paper**.
- When code is not available, the analysis should bind only **figures** and **equations**.
- When shape information, derivations, or implementation details are missing in the paper, the model should explicitly state that they are not provided instead of hallucinating.

## License

Feel free to use and adapt this prompt for academic reading and research workflows.
