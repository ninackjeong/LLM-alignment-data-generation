# LLM-alignment-data-generation

## AIM 3.2.1: LLM Alignment with Empathy using RLHF

### Model Version 1

This model improves upon the foundation model by applying 4 computational rules (voice, tense, pronoun, mood) and augmenting data size.
### Domains
1. **Legal (Tenant Law)**
    - Data: ChatGPT-4 generated dataset with 2,000 questions, each paired with accepted or rejected answers based on the four rules.
    - Dataset link: [Open Australian Legal QA](https://huggingface.co/datasets/umarbutler/open-australian-legal-qa)
2. **Mental Health (Q&A Setting)**
    - Data: Questions sourced from [CounselChat](https://github.com/ninackjeong/LLM-alignment-data-generation/tree/main/public-data/counsel-chat) (Bertagnolli,2020) and [Psych8K](https://github.com/ninackjeong/LLM-alignment-data-generation/tree/main/public-data/psych8k) (Liuetal.,2023a) .
    - Answers generated for each rule using GPT 4o and Claude 3.5 Sonnet.
    - Lastly, Miracle LLM
