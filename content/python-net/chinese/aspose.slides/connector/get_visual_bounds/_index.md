---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
获取形状从其渲染内容计算得到的视觉边界。

### 返回

一个 **aspose.slides.RectangleF**，表示形状的视觉边界
             在幻灯片坐标中。

```python
def get_visual_bounds(self):
    ...
```

### 备注

返回的矩形表示所有内容的轴对齐边界
             这些内容由形状在渲染过程中在幻灯片坐标空间中产生。

这些边界可能与形状的模型边界不同
             ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))
             并且如果渲染的内容超出幻灯片原点，可能包含负坐标。

视觉边界考虑了渲染相关的方面，例如
             变换（例如旋转）、笔画宽度和连接，
             文本布局和溢出、SmartArt 几何形状以及其他布局效果，
             影响形状的最终渲染外观。

返回的边界未被剪裁到幻灯片矩形。

### 另见
* 类 [`Connector`](/slides/python-net/zh/aspose.slides/connector)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)