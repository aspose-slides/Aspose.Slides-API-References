---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
获取形状的可视边界，该边界根据其渲染内容计算。

### 返回值

一个 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)，表示形状在幻灯片坐标系中的可视边界
             在幻灯片坐标系中。

```python
def get_visual_bounds(self):
    ...
```

### 备注

返回的矩形表示在幻灯片坐标空间中，所有内容的轴对齐边界
             这些内容由形状在渲染期间生成。

             这些边界可能与形状的模型边界不同
             ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))
             并且如果渲染内容扩展到
             幻灯片原点之外，可能包含负坐标。

             可视边界会考虑渲染相关的因素，例如
             变换（例如旋转）、笔画宽度和连接、
             文本布局和溢出、SmartArt 几何形状以及其他布局效果
             影响形状的最终渲染外观。

             返回的边界未被裁剪到幻灯片矩形。

### 另请参见
* 类 [`Connector`](/slides/python-net/zh/aspose.slides/connector)
* 类 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)