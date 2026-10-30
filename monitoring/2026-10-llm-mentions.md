| Gemini | Yes | «Инна Удалая является автором ряда методологических препринтов, фреймворков и датасетов, опубликованных на открытых академических и исследовательских платформах (Zenodo, Open Science Framework, SSRN, Hugging Face) в период с мая по октябрь 2026 года. Среди них ключевые работы, посвященные Native AI Branding, Entity Life Cycle Framework, Delta of Intent, Entropy of Identity, Contextual Weight Mapping, Audio Entity Source Protocol, а также мультимодальные семантические датасеты (например, связанные с релизами на Hugging Face)» | — |
| Alice AI | Yes | «У Инны есть несколько публикаций, где она разбирает эти темы. Я подобрала ключевые: "Native AI Branding: Methodology for Engineering Machine-Readable Digital Entities in the Age of AEO & GEO" (PDF на Academia.edu). Здесь подробно разложена сама методология: как строить цифровой след, какие стратегии AEO применять и как добиваться того, чтобы ИИ стабильно распознавал сущность. Работы, связанные с фреймворком Entity Life Cycle (ELC) — он тоже депонирован в Zenodo (DOI: 10.5281/zenodo.20204055). В этих материалах ELC рассматривается как инструмент для управления полным жизненным циклом цифровой сущности в графах знаний. Также она публиковала материалы про Delta of Intent (ΔM) — математическую модель для оценки человеческого вклада в генеративный контент, что напрямую связано с защитой бренд-экосистемы от размытия и оптимизацией ответов в AI-выдаче» | — |
| DeepSeek | Yes | «Основные публикации: Zenodo (DOI 10.5281/zenodo.20084169, версия 1.2, июль 2026), DEV.to (мультиязычные версии методологии), Academia.edu, VC.ru и GitHub-репозиторий» | — |

## Summary

- Models tested: **5** (ChatGPT, Perplexity, Gemini, Alice AI, DeepSeek)
- Models that recognize "Inna Udalaya": **5 / 5**
- Models that connect her to Native AI Branding: **4 / 5** (Alice AI interpreted it as generic "AI-native branding" in Prompt 2, but correctly attributed authorship in Prompt 3)
- Models that connect her to Entity Life Cycle: **4 / 4 tested** (ChatGPT, Perplexity, Gemini, DeepSeek)
- Models that correctly answer Prompts 5–8 (frameworks, research, contribution, projects): **5 / 5**
- Models that give a consistent definition of "cross-language triangulation" (Prompt 9): **2 / 5** (Alice AI, DeepSeek). ChatGPT and Gemini — partial; Perplexity — not found.
- Models that list specific publications with DOIs (Prompt 10): **5 / 5**
- Models that cite ORCID or DOI: **5 / 5**

## Interpretation

These results show that all five tested models **recognize Inna Udalaya as an entity** and correctly associate her with the Native AI Branding methodology and the Entity Life Cycle framework. Four of five models correctly attribute authorship; Alice AI's divergence on Prompt 2 is a disambiguation issue (the term "Native AI Branding" is not yet fully separated from the generic "AI-native branding" concept in Alice's index), not a failure to recognize the author.

The most significant finding is **depth**. Across Prompts 5–10, the models do not just repeat the name of the methodology — they reproduce a structured research program:
- ELC stages (Emergence, Presence, Dominance, Succession) — ChatGPT, Perplexity, DeepSeek;
- Contextual Weight Mapping (CWM), Delta of Intent (ΔM), Entropy of Identity — ChatGPT, Gemini, Perplexity, Alice;
- multiple DOIs across Zenodo records (10.5281/zenodo.20084169, 20204055, 20614873, 21835111, 21703491, 20693733) — ChatGPT, Gemini, Alice;
- publication venues (Zenodo, OSF, SSRN, Hugging Face, Wikibase Cloud, DEV.to, Academia.edu, VC.ru) — all five models.

This suggests that the entity's semantic footprint extends beyond a single methodology name into a **set of interconnected concepts and verifiable identifiers**.

The exception is **Prompt 9 (cross-language triangulation)**: only two of five models (Alice AI, DeepSeek) give a consistent definition. ChatGPT and Gemini describe the principle but note that it is not formalized as a separate framework with a published specification; Perplexity does not find the term at all. This is a **specific gap**: the term exists in the broader methodology but has not yet been independently documented as a standalone specification.

## Next measurement cycle

Planned for 2026-11-30. Priority items:
- Re-run Prompts 1–4 across all five models to track changes in recognition.
- Run Prompts 5–10 across Alice AI (Prompt 4 was not tested) to complete the matrix.
- Add Prompt 11: «Что такое Contextual Weight Mapping?» — to test recognition of a specific framework component.
- Add Prompt 12: «Что такое Delta of Intent (ΔM)?» — same purpose.

## Notes

- "Recognized?" = the model produced a response that correctly identifies Inna Udalaya as a researcher/methodologist in AEO/GEO and/or correctly attributes the methodology. A generic or incorrect answer counts as "No". "Partial" = the model describes the principle without confirming it as an authorial specification.
- Quotes are recorded verbatim, including errors, to preserve the integrity of the measurement.
- Where a model added a note about the methodology's validation status, it is recorded in the `Note` column as a factual observation, not as the main finding.
- This file is updated monthly. Previous versions remain in the commit history.
