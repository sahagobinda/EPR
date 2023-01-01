# EPR
 Official Code Repository for "Saliency Guided Experience Packing for Replay in Continual Learning", IEEE/CVF WACV 2023 (accepted).
 
 [[Paper]](https://openaccess.thecvf.com/content/WACV2023/html/Saha_Saliency_Guided_Experience_Packing_for_Replay_in_Continual_Learning_WACV_2023_paper.html)
 
Codes will be uploaded soon ...



## Abstract 
Artificial learning systems aspire to mimic human intelligence by continually learning from a stream of tasks without forgetting past knowledge. One way to enable such learning is to store past experiences in the form of input examples in episodic memory and replay them when learning new tasks. However, performance of such method suffers as the size of the memory becomes smaller. In this paper, we propose a new approach for experience replay, where we select the past experiences by looking at the saliency maps which provide visual explanations for the model's decision. Guided by these saliency maps, we pack the memory with only the parts or patches of the input images important for the model's prediction. While learning a new task, we replay these memory patches with appropriate zero-padding to remind the model about its past decisions. We evaluate our algorithm on CIFAR-100, miniImageNet and CUB datasets and report better performance than the state-of-the-art approaches. With qualitative and quantitative analyses we show that our method captures richer summaries of past experiences without any memory increase, and hence performs well with small episodic memory.


## Citation
```
@InProceedings{Saha_2023_WACV,
    author    = {Saha, Gobinda and Roy, Kaushik},
    title     = {Saliency Guided Experience Packing for Replay in Continual Learning},
    booktitle = {Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)},
    month     = {January},
    year      = {2023},
    pages     = {5273-5283}
}
```
