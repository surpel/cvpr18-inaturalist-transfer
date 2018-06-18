# Large Scale Fine-Grained Categorization and Domain-Specific Transfer Learning

This repository contains the **iNaturalist mini validation set** (./inat_minival.txt) used in our paper:

[*Large Scale Fine-Grained Categorization  and Domain-Specific Transfer Learning*](https://vision.cornell.edu/se3/wp-content/uploads/2018/03/FGVC_CVPR_2018.pdf)\
[Yin Cui](http://www.cs.cornell.edu/~ycui/), [Yang Song](https://ai.google/research/people/author38270), [Chen Sun](http://chensun.me/), Andrew Howard, [Serge Belongie](http://blogs.cornell.edu/techfaculty/serge-belongie/)\
CVPR 2018

The mini validation set contains 9,697 images that are randomly selected from the original iNaturalist 2017 validation set. We used the rest of valdiation images together with the training set to train our model in the paper.

We plan to release the code and pre-trained models soon under the umbrella of [Tensorflow Hub](https://www.tensorflow.org/hub/). Please stay tuned.

## Citation
If you find our work helpful in your research, please cite it as:
```latex
@inproceedings{Cui2018iNatTransfer,
  title = {Large Scale Fine-Grained Categorization and Domain-Specific Transfer Learning},
  author = {Yin Cui, Yang Song, Chen Sun, Andrew Howard, Serge Belongie},
  booktitle={CVPR},
  year={2018}
}
```