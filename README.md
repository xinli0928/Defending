Overview
----
This repository is an implementation of the paper "[Defending against adversarial attacks on medical imaging AI system, classification or detection?
](https://arxiv.org/abs/2006.13555)".

OCT Images Dataset
-----
* OCT Images (108,312 Images)
  * [Identifying Medical Diagnoses and Treatable Diseases by Image-Based Deep Learning.](https://data.mendeley.com/datasets/rscbjbr9sj/2)  


Model Training and Evaluation
----
Codes and learned model parameters are available in the Main folder. Here are the steps for training and testing:

* Put the OCT images in the Dataset folder as the following structure:


```
Dataset
   train
      CNV
      DME
      DRUSEN
      NORMAL
   test
      CNV
      DME
      DRUSEN
      NORMAL
   validation
      CNV
      DME
      DRUSEN
      NORMAL
```
* Run the .ipynb file for model training and testing.  



Citation
------
```
Xin Li, Deng Pan and Dongxiao Zhu
Defending against adversarial attacks on medical imaging AI system, classification or detection?
https://github.com/xinli0928/Defending/
```

```
@misc{li2020defending,
      title={Defending against adversarial attacks on medical imaging AI system, classification or detection?}, 
      author={Xin Li and Deng Pan and Dongxiao Zhu},
      year={2020},
      eprint={2006.13555},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```
