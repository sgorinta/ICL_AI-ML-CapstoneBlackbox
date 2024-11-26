# ICL_AI-ML-CapstoneBlackbox
Purpose

This project represents my first capstone for the Imperial College London (ICL) Professional Certificate in AI and Machine Learning, focusing on Blackbox Optimization. I’m sharing the notebooks I developed for the associated competition, along with an overview of the assignment. Although the functions themselves aren’t publicly accessible, these examples of basic Naive Bayes optimization code snippets can guide beginners in Machine Learning to gain practical experience and build confidence.

Project Details

We tackled eight unknown functions using Bayesian Optimization, aiming to maximize all eight functions despite limited context and varying input dimensions. Each function had distinct characteristics and complexities. Additionally, querying these functions came with significant constraints—we could only submit a query for a function every few days!

Input Dimensions:
- Function 1: 2-dimensional  
- Function 2: 2-dimensional  
- Function 3: 3-dimensional  
- Function 4: 4-dimensional  
- Function 5: 4-dimensional  
- Function 6: 5-dimensional  
- Function 7: 6-dimensional  
- Function 8: 8-dimensional  

Context for Each Function is

1. Searching for Contamination Sources - A  two-dimensional optimization problem involving identifying radiation sources within a square area. Radiation is detectable only at close range, leading to sparse observations. There are two sources, one less hazardous than the other, and your goal is to locate both effectively.

2. Optimising Noisy Models - This scenario involves maximising the log-likelihood of an unknown machine learning model. Due to critical initialization dependencies, the observations are highly noisy and filled with local optima, making it a complex two-dimensional optimisation problem.

3. Drug Discovery Problem - A 3-dimensional problem in drug discovery where you select three compounds to form a drug. The aim is to minimise adverse reactions, measured by the output. One compound might have no impact, adding an extra layer of complexity.

4. Fast but Inaccurate Modeling - This involves a 4-dimensional task of tuning hyperparameters for a machine learning model used in business logistics. The goal is to approximate optimal warehouse product placements. While precise computations are computationally prohibitive, this fast model gives quick but noisy approximations, making it challenging to navigate local optima.

5. Yield in a Chemical Reaction - This problem involves maximising the yield of a chemical process in a 4-dimensional input space. The process is unimodal, which can simplify finding the optimal chemical combination to maximise output.

6. Cake and Stuff - A  5-dimensional optimisation where you’re designing a cake recipe. The model scores your recipe based on multiple objectives: flavor, consistency, calories, waste, and cost. The goal is to bring the total score, reflecting these competing metrics, as close to zero as possible.

7. Sometimes Lazy is Best - This task involves optimizing six hyperparameters of a commonly used machine learning model. Given the popularity of this model, leveraging existing research or prior optimizations might help streamline the process.

8. High-Dimensional Optimization - The final challenge is an 8-dimensional optimisation problem. High-dimensional black-box optimisation is  difficult, so focusing on effective local solutions can be a pragmatic approach.
