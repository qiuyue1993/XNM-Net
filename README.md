# This repository is forked from [here](https://github.com/shijx12/XNM-Net)

## Requirements
- python==3.6
- pytorch==0.4.0
- h5py 
- tqdm
- matplotlib


## Experiments
They have 4 experiment settings:
- CLEVR dataset, Det setting (i.e., using detected scene graphs). Codes are in the directory `./exp_clevr_detected`.
- CLEVR dataset, GT setting (i.e., using ground truth scene graphs), attention is computed by softmax function over the label space. Codes are in `./exp_clevr_gt_softmax`.
- CLEVR dataset, GT setting, attention is computed by sigmoid function. Codes are in `./exp_clevr_gt_sigmoid`.
- VQA2.0 dataset, detected scene graphs. Codes are in `./exp_vqa`.


## Acknowledgement
- The original authors refer to the repo [clevr-iep](https://github.com/facebookresearch/clevr-iep) for preprocessing codes.
- The original implementations of module model and dataloader are based on [tbd-net](https://github.com/davidmascharka/tbd-nets).
- The original authors stacked neural module implementation in `./exp_vqa` is based on Hu's [StackNMN](https://github.com/ronghanghu/snmn).

