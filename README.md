# TVGQS Dataset
 
The TVGQS (Tagged VideoGame Quests Sequences) is a dataset containing mutiple quests dialogues. The dataset is a .txt file, in which each line represents a quest sentences. It (currently) contains 457 pieces, obtained from [LIGHT](https://paperswithcode.com/dataset/light-quests) datset; The Torchlight datset from [videogame text corpora](https://github.com/hmi-utwente/video-game-text-corpora); [Quest Description Generator](https://www.fantasynamegenerators.com/quest-descriptions.php) and some [ChatGPT](https://chat.openai.com/)-generated (usually, these ones are only the quest objective, having no context).

# Data Annotation

We designed a way to format the dataset based of tags. First, we have the <> tags. The < SOS >¹ and < EOS > tags represent the Start and the End Of a Sequence. The < SOA >/< EOA >¹ tags represent the Start and the End Of a Action (mission objective). Also, we have the [ ] tags. These tags represent items and names that are game-specific (e.g.: a character's name or a city's name) and they generalize every quest to be game-independent. They are:
* [CHARACTER];
* [ITEM];
* [PLACE];
* [ENEMY];
* [NUMBER].

--- 
¹ Formatted whithout whitespaces on dataset.

# Citing this Dataset

Please, cite:

```
@misc { zardo_fiorio_feijo_2023,
 title={TVGQS}
 author={Zardo, Rafael; Fiorio, Pedro and dos Santos, André Luiz F.},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/rafazardo/tvgqs}}
}
```
