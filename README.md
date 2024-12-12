<div align="center">

# CBraMod


_A Criss-Cross Brain Foundation Model for EEG Decoding_

[![Paper](https://img.shields.io/badge/paper-2412.07236-red)](https://arxiv.org/abs/2412.07236)
[![huggingface](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Models-FFD21E)](https://huggingface.co/weighting666/CBraMod)
![GitHub Repo stars](https://img.shields.io/github/stars/wjq-learning/CBraMod)

</div>


<div align="center">
<img src="figure/CBraMod_logo.png" style="width: 15%;" />
</div>


## 🔍 About
We propose **CBraMod**, a novel EEG foundation model, for EEG decoding on various clinical and BCI application.
<div align="center">
<img src="figure/model.png" style="width:80%;" />
</div>

## 🔥 How to Pretrain
You can pre-train CBraMod on our pre-training dataset or your own custom pre-training dataset using the following code:
```bash
python pretrain_main.py
```


## 🔧 Updating...



## 🔗 Citation
If you're using this repository in your research or applications, please cite using the following BibTeX:
```bibtex
@misc{wang2024cbramod,
      title={CBraMod: A Criss-Cross Brain Foundation Model for EEG Decoding}, 
      author={Jiquan Wang and Sha Zhao and Zhiling Luo and Yangxuan Zhou and Haiteng Jiang and Shijian Li and Tao Li and Gang Pan},
      year={2024},
      eprint={2412.07236},
      archivePrefix={arXiv},
      primaryClass={eess.SP},
      url={https://arxiv.org/abs/2412.07236}, 
}
```