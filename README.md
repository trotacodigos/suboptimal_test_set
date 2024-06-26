# The Suboptimal WMT Test Sets and Their Impact on Human Parity
<img src="https://img.shields.io/badge/Python-3766AB?style=flat-square&logo=Python&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Kakao-FFCD00?style=flat-square&logo=Kakao&logoColor=black"/></a>
                                                                                               

This repository provides codes and datasets for the NMT evaluation for the following publication, "The Suboptimal WMT Test Sets and Their Impact on Human Parity" by Ahrii Kim, Yunju Bak, Jimin Sun, Sungwon Lyu, and Changmin Lee, submitted at [Preprints.org](https://www.preprints.org).

-----
### About
We propose that the low quality of the source test set of the news track at WMT 2020 may lead to an overrated human parity claim. This is proved by performing a Relative Ranking human evaluation which is later analyzed by Significance Test and Absolute Ranking scores. We report that:
   - About 5% of the segments that have previously achieved a human parity claim turn out to be statistically invalid.
   - The proportion reaches up to 7% when the "contaminated" sentences are solely computed.
   - The absolute ranking score drops in all MT models while .


### Dataset
- Language Pair: EN -> KO
- Original English Source: WMT 2020 English-III test set
- Volume: 437 sentences
- System: 2 online models (MT_Y, MT_Z)
- Comparison: 
   - before-test-set (BTS) vs. after-test-set (ATS)
   - Human Translation(HT) vs. MT_Y vs. MT_Z
   - Google Translate (as a benchmark model)

### Code

To install packages, please refer to `requirements.txt`

```sh
# run main score code
cd evalutation
python score.py > out.txt
```

### Paper 

#### Bibtex ([preprinted ver.](https://www.preprints.org/manuscript/202110.0199/v1))

    @article{kim-et-al-21-testset,
      author =       "Ahrii Kim and Yunju Bak and Jimin Sun and Sungwon Lyu and Changmin Lee",
      title =        "The Suboptimal WMT Test Sets and Their Impact on Human Parity",
      journal =      "Preprints",
      year =         "2021",
      doi = "10.20944/preprints202110.0199.v1"
    }


 
#### Contact
For more questions, please contact the first author of the paper.



  
  

