# VGG

| 模型          | 模型大小    | 训练时长                 | kaggle猫狗分类分数/排名 |
|-------------|---------|----------------------|-----------------|
| AlexNet     | 228.1MB | 20min/3Epoch(需要重新测量) | 0.97814(1113)   |
| VGG         | 537.1MB | 30min/3Epoch(需要重新测量) | 0.41999(907)    |
| googleLeNet |         |                      |                 |

## 训练技巧

尺度扰动

## 保存模型

```python
torch.save(alexnet_model.state_dict(),'../data/self_train.pth')
```


```python
torch.save(alexnet_model,'../data/self_train.pth')
```


update