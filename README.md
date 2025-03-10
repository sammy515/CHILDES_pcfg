# CHILDES_pcfg

Modified CHILDES corpora for an educational exercise using [https://www.nltk.org/](https://www.nltk.org/) to induce probablistic context free grammars from caretaker speech and then parse child speech.

Contains corpora of speech transcripts from two longitudinal studies: **Peter** ([Bloom et al. 1974](https://childes.talkbank.org/access/Eng-NA/Bloom.html)) and **Laura** ([Braunwald 1971](https://childes.talkbank.org/access/Eng-NA/Braunwald.html)). Corpora are arranged by age of the child and 

I've modified the corpora ending in _MOT from their original forms to just contain constituent trees of the mothers' speech. The part of speech tags are retained from the original [CHILDES annotation](https://talkbank.org/manuals/MOR.html#_Toc65933295), and compound POS tags are split.
The constituent trees have been constructed based on a combination of these POS tags, the dependency parses originally in the CHILDES corpora, and [these dependency->constituent algorithms](https://github.com/wenkokke/dep2con/tree/eec24bc8e1a4db5b1582f0fd933ab02f8a6ce041).

