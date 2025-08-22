# PersonaConflicts Corpus

A dataset of naturalistic simulated dialogues featuring interpersonal conflicts between familiar social partners with rich personal backstories.

## Dataset Overview

This corpus contains **5,772** naturalistic simulated dialogues spanning diverse conflict scenarios between friends, family members, and romantic partners. The dataset is designed to evaluate how relationship backstory influences both human and model perception of conflicts in conversation.

## Dataset Files

### Core Dataset
- **`dataset_final.csv`** - Contains all simulated conversations with dialogue turns and metadata

### Human Annotations
- **`mturk_aggregate.csv`** - Combined annotations across 2 annotators for a subset of dialogues
- **`mturk_negative_backstory.csv`** - Subset annotated by MTurk workers with negative relationship backstories
- **`mturk_positive_backstory.csv`** - Subset annotated by MTurk workers with positive relationship backstories

### Supporting Data
- **`sotopia_agent_profiles.csv`** - Information about the simulated characters including their personalities, backgrounds, and relationship dynamics
- **`Interpersonal_Conflict_Scenarios.csv`** - Contains the scenario types that set up the conflicts, including different conflict categories and triggers

## Research Context

This dataset was created to address the gap in NLP research on conflict detection, which typically treats conflicts as general tasks without considering the relational dynamics that influence how messages are perceived. The corpus leverages nonviolent communication (NVC) theory to evaluate how relationship backstory affects both human and model perception of conversational breakdowns.


## Citation

If you use this dataset in your research, please cite our paper:

```
@inproceedings{shen2025words,
  title={Words Like Knives: Backstory-Personalized Modeling and Detection of Violent Communication},
  author={Shen, Jocelyn and Yerukola, Akhila and Zhou, Xuhui and Breazeal, Cynthia and Sap, Maarten and Park, Hae Won},
  booktitle={Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing},
  year={2025},
  url={https://2025.emnlp.org/}
}
```
<!-- 
**Paper:** Words Like Knives: Backstory-Personalized Modeling and Detection of Violent Communication  
**Authors:** Jocelyn Shen, Akhila Yerukola, Xuhui Zhou, Cynthia Breazeal, Maarten Sap, Hae Won Park  
**Conference:** EMNLP 2025  
**URL:** https://2025.emnlp.org/ -->