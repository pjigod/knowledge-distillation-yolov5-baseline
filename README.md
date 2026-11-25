# knowledge-distillation-yolov5-baseline

知识蒸馏实验使用的 YOLOv5 基线代码，作为后续改进方法的对照。基于 [Ultralytics YOLOv5](https://github.com/ultralytics/yolov5)。

## 本仓库包含

- YOLOv5 模型与配置。
- 训练、验证、预测和导出工具。

## 基线训练

进入 `yolov5` 目录，安装依赖并运行训练：

```powershell
pip install -r requirements.txt
python train.py --data data/your_dataset.yaml --weights yolov5s.pt --img 640 --epochs 150
```

将 `data/your_dataset.yaml` 换成自己的数据集配置。此示例使用 YOLOv5s 预训练权重。

## 来源

- 上游代码：[ultralytics/yolov5](https://github.com/ultralytics/yolov5)
- 许可证：AGPL-3.0，详见上游仓库的 `LICENSE`
