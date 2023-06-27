# eegCollection
eeg code and paper Collection
| Model |论文|time|Dataset|框架|Realted| Description |
| --- | --- | --- | --- | --- | --- | --- | 
| DL_EEG ||||Pytorch |[Code](https://github.com/edw4rdyao/DL_EEG#public-datasets)|运动想象eeg合集，包括多种模型，要好好看看|
| GCN |Convolutional Neural Networks on Graphs with Fast Localized Spectral Filtering|2016||Pytorch&tf|[Code1/](https://github.com/magnumical/MNE_GCN)[Code2/](https://github.com/magnumical/GCN_for_EEG)[rawCode](https://github.com/mdeff/cnn_graph)|Coarseing那个代码多种版本|
| FB-GCNN ||||Pytorch |[Code](https://github.com/yff12345/FB-GCNN)|Coarseing那个代码的pytorch版本，有chebshev_gcnn.Py|
| EEGGENET | EEG_GENet：A Feature-Level Graph Embedded Method for Motor Imagery Classification based on EEG Signal |2022|Bciciv-2a 79.57%;high_Gamma 96.02%|Pytorch|[Code](https://github.com/stickOverCarrot/EEGGENET)|基于braindecode库|
| cnn-eeg | An end-to-end deep learning approach to MI-EEG signal classification for BCIs. Expert Systems with Applications |2018|Physionet 58.8%，68.51%|tf & keras|[Code](https://github.com/hauke-d/cnn-eeg)|有可视化的部分可以拿来用；迁移学习？|
| Brain_EEGAT | EEG-GAT: Graph Attention Networks for Classification of Electroencephalogram (EEG) Signals |2022|Physionet(睡眠) 58.09%|Pytorch|[Code](https://github.com/AIRightGpl/Brain_EEGAT)|代码比较乱，可以参考其中的模型|
| GCN、GAT、GraphSAGE、deepwalk、node2vec ||||Pytorch |[Code1/](https://github.com/shuxinyin/Graph-Learning)[Code2](https://github.com/dsgiitr/graph_nets)|可以参考学习|
| EEGNet | EEGNet: A Compact Convolutional Network for EEG-based Brain-Computer Interfaces |2016||Pytorch&tf |[PytCode/](https://github.com/aliasvishnu/EEGNet)[tfCode](https://github.com/vlawhern/arl-eegmodels)||
| GAT | Graph Attention Networks |2017||Pytorch&tf|[PytCode/](https://github.com/Diego999/pyGAT)[tfCode](https://github.com/PetarV-/GAT)||
| LTS-GAT-model | Locally temporal-spatial pattern learning with graph attention mechanism for EEG-based emotion recognition |2022||Pytorch |[Code](https://github.com/CFSRgroup/LTS-GAT-model)|只有网络模型，情感eeg|
| eegnet-based-embedded-bci | An Accurate EEGNet-based Motor-Imagery Brain--Computer Interface for Low-Power Edge Computing |2020|Physionet 65.07% |tf |[Code](https://github.com/MHersche/eegnet-based-embedded-bci)||
| EEG-Conformer | EEG Conformer: Convolutional Transformer for EEG Decoding and Visualization |2022|bciiv2a 78.66% |pytorch |[Code](https://github.com/eeyhsong/EEG-Conformer)|可以借鉴注意力部分|
| GSNN | Graph Stochastic Neural Networks for Semi-supervised Learning |2022|cora |pytorch |[Code](https://github.com/GSNN/GSNN)|比较新的idea|
| ECML-PKDD_MMCNN | A Multi-branch Multi-scale Convolutional Neural Network for Motor Imagery Classification. |2020|bci2a 0.814 |tf |[Code](https://github.com/jingwang2020/ECML-PKDD_MMCNN)|多分支多规模|
| RNN_LSTM |  ||bci |tf |[Code](https://github.com/shariharan205/Motor-Imagery-Tasks-Classification-using-EEG-data)||
| EEG-motor-imagery | GCN-Explain-Net: An Explainable Graph Convolutional Neural Network (GCN) for EEG-based Motor Imagery Classification and Demystification ||Physionet 76.95% |pytorch |[Code](https://github.com/shariharan205/Motor-Imagery-Tasks-Classification-using-EEG-data)|没找到论文|
| eeg-gnn-ssl | Self-Supervised Graph Neural Networks for Improved Electroencephalographic Seizure Analysis |2022| |pytorch |[Code](https://github.com/tsy935/eeg-gnn-ssl)|癫痫数据集，可以借鉴可视化|
| DGCNN | EEG Emotion Recognition Using Dynamical Graph Convolutional Neural Networks |2022| |pytorch |[Code](https://github.com/xueyunlong12589/DGCNN)|情感数据集,切比雪夫gcn代码可供学习|



