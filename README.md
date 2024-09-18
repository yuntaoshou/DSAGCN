[stars-img]: https://img.shields.io/github/stars/yuntaoshou/DSAGCN?color=yellow
[stars-url]: https://github.com/yuntaoshou/DSAGCN/stargazers
[fork-img]: https://img.shields.io/github/forks/yuntaoshou/DSAGCN?color=lightblue&label=fork
[fork-url]: https://github.com/yuntaoshou/DSAGCN/network/members
[AKGR-url]: https://github.com/yuntaoshou/DSAGCN

# Conversational emotion recognition studies based on graph convolutional neural networks and a dependent syntactic analysis
By Yuntao Shou, Tao Meng, Wei Ai, Sihan Yang, Keqin Li. [[paper link]](https://www.researchgate.net/publication/363002926_Conversational_emotion_recognition_studies_based_on_graph_convolutional_neural_networks_and_a_dependent_syntactic_analysis)

[![GitHub stars][stars-img]][stars-url]
[![GitHub forks][fork-img]][fork-url]

This is an official implementation of 'Conversational emotion recognition studies based on graph convolutional neural networks and a dependent syntactic analysis' :fire:. Any problems, please contact shouyuntao@stu.xjtu.edu.cn. If you find this repository useful to your research or work, it is really appreciated to star this repository :heart:.

<div  align="center"> 
  <img src="https://github.com/yuntaoshou/DSAGCN/blob/main/fig/DSAGCN.png" width=100% />
</div>



## 🚀 Installation

```bash
Python 3.8.5
torch 1.7.1
CUDA 11.3
torch-geometric 1.7.2
```

## Training
```bash
python train.py --base-model 'GRU' --dropout 0.5 --lr 0.0001 --batch-size 16 --graph_type='hyper' --epochs=0 --graph_construct='direct' --multi_modal --mm_fusion_mthd='concat_DHT' --modals='avl' --Dataset='IEMOCAP'
```

If our work is helpful to you, please cite:
```bash
@article{shou2022conversational,
  title={Conversational emotion recognition studies based on graph convolutional neural networks and a dependent syntactic analysis},
  author={Shou, Yuntao and Meng, Tao and Ai, Wei and Yang, Sihan and Li, Keqin},
  journal={Neurocomputing},
  volume={501},
  pages={629--639},
  year={2022},
  publisher={Elsevier}
}
```

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yuntaoshou/DSAGCN&type=Date)](https://star-history.com/#yuntaoshou/DSAGCN&Date)
