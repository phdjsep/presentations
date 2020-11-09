# Reproducible computation at scale in R with targets

Ambitious workflows in R, such as machine learning analyses, can be difficult to manage. A single round of computation can take several hours to complete, and routine updates to the code and data tend to invalidate hard-earned results. You can enhance the maintainability, hygiene, speed, scale, and reproducibility of such projects with the targets R package. targets resolves the dependency structure of your analysis pipeline, skips tasks that are already up to date, executes the rest with optional distributed computing, and manages data storage for you. It surpasses the permanent limitations of its predecessor, drake, and provides increased efficiency and a smoother user experience. This talk demonstrates how to create and maintain a Bayesian model validation project using targets-powered automation.