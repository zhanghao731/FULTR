# FULTR: A Large-scale Prior-Posterior Fusion Learning to Rank Dataset and its application for Satisfaction-Oriented Ranking
In this paper, we introduce FULTR–a large-scale, prior-posterior <ins>FU</ins>sion <ins>LTR</ins> dataset. FULTR comprises over 224M queries and 683M documents from [Baidu Search](https://www.baidu.com), combining both: (1) a rich prior-attribute set with detailed textual relevance, authority, recency, and quality features, and (2) a comprehensive posterior-attribute set enriched by user click data, dwell time, and positional information.
## Dataset Folder Structure
The dataset is organized as follows:
```
FULTR/
├── prior/ # prior-attribute set
│ ├── train.gz
│ ├── test.gz
├── posterior/ # posterior-attribute set
│ ├── train/
│ │ ├──part-00005.gz
│ │ ├──part-00006.gz
│ │ ├──...
│ │ ├──part-00105.gz
│ ├── test/
│ │ ├──part-00001.gz
│ │ ├──part-00002.gz
│ │ ├──part-00003.gz
│ │ ├──part-00004.gz
│ │ ├──part-00005.gz
```
## Download the Dataset
You can download the dataset using the link: [Download Dataset](https://pan.baidu.com/s/1LGgRHuy5bFKIFqWvsNVl9A?pwd=pg9c). Due to legal restrictions with Baidu, we only made part of the training set of the posterior-attribute set available. If you want the full data, please contact the authors and explain the reason for using this dataset.
## Quick Start
The code for training models using this dataset will be released soon. Stay tuned for updates!
## License
This dataset is licensed under the [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) license. You are free to share and adapt the dataset for **non-commercial purposes**, but proper attribution is required. For commercial use, please contact the authors.
## Contact
For any questions or suggestions, please contact:  
**EMAIL**: yuchenli1230 {at} gmail.com
