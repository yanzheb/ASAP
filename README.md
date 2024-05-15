# ASAP: Attention-Based State Space Abstraction for Policy Summarization

This repository contains code for the abovementioned paper.

## Information

To reproduce the results for ASAP, as shown in the paper, run the Jupyter notebook named "results.ipynb". The repository includes the models used in the experiments with their Tensorboard log files, so you do not need to retrain yourself if you want to reproduce the results. They are stored in the folder named "runs."

To train ASAP from scratch, use the file "cluster_importance.py." The "requirements.txt" was made later, so it does not contain identical versions of packages as I initially used, but they produce the same results as far as I can tell.

The hyperparameters used to train ASAP are stored in the folder "configs."

## Citation

```lang-tex
@inproceedings{DBLP:conf/acml/BekkemoenL23,
  author       = {Yanzhe Bekkemoen and
                  Helge Langseth},
  title        = {{ASAP:} Attention-Based State Space Abstraction for Policy Summarization},
  booktitle    = {Proc. of ACML},
  year         = {2023},
  url          = {<https://proceedings.mlr.press/v222/bekkemoen24a.html}>,
  bibsource    = {dblp computer science bibliography, <https://dblp.org}>
}
```
