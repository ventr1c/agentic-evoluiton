# Position: Agentic Evolution is the Path to Evolving LLMs
Official repository of "Position: Agentic Evolution is the Path to Evolving LLMs" [[paper](https://arxiv.org/abs/2602.00359)]

## Status

- [x] Implementation completed
- [ ] Open-source release (pending internal review)

## Overview of agentic evolution
![Overview of Agentic Evolution](figures/framework_evolution.jpg)


## Overview of A-Evolve
![Overview of A-Evolve](figures/a_evolve_framework.jpg)

## Abstract 
As Large Language Models (LLMs) move from curated training sets into open-ended real-world environments, a fundamental limitation emerges: static training cannot keep pace with continual deployment environment change. Scaling training-time and inference-time compute improves static capability but does not close this train–deploy gap. We argue that addressing this limitation requires a new scaling axis—evolution. Existing deployment-time adaptation methods, whether parametric fine-tuning or heuristic memory accumulation, lack the strategic agency needed to diagnose failures and produce durable improvements. Our position is that agentic evolution represents the inevitable future of LLM adaptation, elevating evolution itself from a fixed pipeline to an autonomous evolver agent. We instantiate this vision in a general framework, A-Evolve, which treats deployment-time improvement as a deliberate, goal-directed optimization process over persistent system state. We further propose the evolution-scaling hypothesis: the capacity for adaptation scales with the compute allocated to evolution, positioning agentic evolution as a scalable path toward sustained, open-ended adaptation in the real world.
