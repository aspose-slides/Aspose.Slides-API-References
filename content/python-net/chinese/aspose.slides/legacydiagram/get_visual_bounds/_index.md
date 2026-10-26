---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
获取从渲染内容计算得到的形状的可视边界。

### 返回值

一个 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)，表示形状在幻灯片坐标系中的可视边界。

```python
def get_visual_bounds(self):
    ...
```

### 备注

返回的矩形表示所有内容的轴对齐边界
             由形状在幻灯片坐标空间渲染期间产生。

这些边界可能与形状的模型边界 ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height)) 并且如果渲染的内容超出幻灯片原点，可能包含负坐标。

可视边界会考虑渲染相关的因素，例如
             变换（如旋转）、线宽和接合、
             文本布局和溢出、SmartArt 几何形状，以及其他
             影响形状最终渲染外观的布局效果。

返回的边界不会被裁剪到幻灯片矩形内。

### 另见
* 类 [`LegacyDiagram`](/slides/python-net/zh/aspose.slides/legacydiagram)
* 类 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)