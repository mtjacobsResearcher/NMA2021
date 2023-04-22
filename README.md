# NMA2021
A copy of the project I worked on in 2021 for Neuromatch Academy's Computational Neuroscience Intensive. 

Authors include:
-Matthew Jacobs
-Bahareh Najafi
-Alina Tu
-Colleen Fleury
-Nan Zhang
-Shreeja Dutta

Project Abstract: 
The early visual networks have been clearly mapped, but more abstracted representations of stimuli within working memory are less mapped out. Research showed that some areas have preference for certain types of stimuli (e.g., the fusiform face area’s correlation with faces); building on this we aim to find networks that arise when an individual is actively focused on a categorical representation during a working memory task. Specifically, we explore which regions are correlated to each other during separate runs of N-back working memory tasks with categorically-different visual stimuli. Provided the existing literature on specific brain regions that are activated when individuals are shown visual stimuli of a particular category, we hypothesize that during the N-back task, the information coming from such regions would be communicated/processed with the brain region modulating working memory. We performed a generalized linear model on the Human Connectome Project dataset and cross-correlated the weights within a representational similarity analysis for each condition. To obtain the highly correlated regions for each condition, we first performed dimensionality reduction to cross-correlation matrices and applied k-means clustering to the scaled values. The evidence supports that categorical representation is modularized, which suggests that processes, such as working memory, engage these modules rather than represent the category redundantly elsewhere.

[Project Slideshow](https://docs.google.com/presentation/d/1kpaM5QFX4NwmsLm9brjoavPop21v97coXj39IUlNJEk/edit?usp=sharing)

[Project Notebook](https://colab.research.google.com/drive/1d9AKFjCotrjyp6oboP4jQC4YKnz9AkJH?usp=sharing)

Note about project:

The course is only 3 weeks including 6 hours of coursework per day. We did our best to keep the code clean, but in the final pushes, the cells have come out of order. If there is interest in the functioning code, I can fix it. Being that it is a quick student project, I haven't taken the time to clean it up. 


[Neuromatch Academy](https://academy.neuromatch.io/)
