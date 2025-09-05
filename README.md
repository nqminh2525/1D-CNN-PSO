# 1D-CNN-PSO
# English version description
Source code implementation for the research project: "CNN Configuration Optimization for IoT Attack Detection Problem"
This project presents an enhanced approach based on the original research by [Kilichev et al.] (https://www.mdpi.com/2227-7390/11/17/3724). Part of the research ideas have been published in the paper: ["A Novel Approach for 1D-CNN Hyperparameter Optimization in IoT Attack Detection using Particle Swarm Optimization"](https://isj.vn/index.php/journal_STIS/article/view/1097)
## File Structure
The naming convention for each file is as follows:
- 0.x (0.0 and 0.1): Original research implementation
- 1.x (1.0 and 1.1): Enhanced implementation from this project
- x.0 (0.0 and 1.0): Code files using fitness function based on original research (single-objective: model accuracy only)
- x.1 (0.1 and 1.1): Code files using proposed fitness function (multi-objective: combining model accuracy and execution time)
## File Description
- w=0.5 represents the balance weight between accuracy and execution time in the multi-objective fitness function
