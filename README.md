# DNGI-MER
Dynamic Noise-Reduction and Granularity-Aware Interaction Fusion for Multimodal Emotion Recognition

## 作者与单位
- **作者**：Huan Zhao, Yong Wei, Zhijie Yu, KeHan Wang
- **单位**：College of Computer Science and Electronic Engineering, Hunan University
- **通讯作者**：KeHan Wang (wangkh@hnu.edu.cn)
- **基金支持**：National Natural Science Foundation of China (Grant 62076092)

## 实验设置
### 数据集
选用多模态情感识别两大经典基准数据集（情感回归任务，评分范围$[-3,3]$）：
| 数据集 | 样本量 | 训练/验证/测试划分 |
|--------|--------|--------------------|
| CMU-MOSI | 2199 utterances | 1284/229/686 |
| CMU-MOSEI | 23454 utterances | 16326/1871/4659 |

## 实验结果
DNGI-MER在CMU-MOSI和CMU-MOSEI上全面超越主流SOTA基线，关键指标如下（最优结果）：
| 数据集 | MAE↓ | Corr↑ | ACC-2 (neg/pos)↑ | F1 (neg/pos)↑ | ACC-7↑ |
|--------|------|-------|------------------|---------------|--------|
| CMU-MOSI | 0.510 | 0.816 | 87.0/89.2 | 87.0/89.1 | 49.3 |
| CMU-MOSEI | 0.470 | 0.801 | 86.6/88.5 | 86.2/88.5 | 56.6 |

## 引用格式
```bibtex
@article{DNGI-MER2025,
  title={Dynamic Noise-Reduction and Granularity-Aware Interaction Fusion for Multimodal Emotion Recognition},
  author={Zhao, Huan and Wei, Yong and Yu, Zhijie and Wang, KeHan},
  journal={[Under Review]},
  year={2025},
  affiliation={College of Computer Science and Electronic Engineering, Hunan University}
}
```
