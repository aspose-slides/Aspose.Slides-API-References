---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
获取形状的可视边界，该边界根据其渲染内容计算得出。

### 返回
一个 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)，表示形状在幻灯片坐标系中的可视边界。
             
```python
def get_visual_bounds(self):
    ...
```

### 备注
返回的矩形表示形状在渲染过程中产生的所有内容在幻灯片坐标空间中的轴对齐边界。
             
这些边界可能与形状的模型边界 ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height)) 不同，并且如果渲染内容超出幻灯片原点，可能包含负坐标。
             
可视边界会考虑渲染相关的各方面因素，例如转换（例如旋转）、笔画宽度和连接、文本布局与溢出、SmartArt 几何以及其他影响形状最终渲染外观的布局效果。
             
返回的边界未被裁剪到幻灯片矩形。

### 另请参见
* 类 [`Chart`](/slides/python-net/zh/aspose.slides.charts/chart)
* 类 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)