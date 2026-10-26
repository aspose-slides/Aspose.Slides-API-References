---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
获取形状的视觉边界，该边界根据其渲染内容计算得到。

### 返回

一个 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef) 表示形状的视觉边界
             在幻灯片坐标系中。

```python
def get_visual_bounds(self):
    ...
```

### 备注

返回的矩形表示所有内容的轴对齐边界
             这些内容是在渲染过程中由形状在幻灯片坐标空间中生成的。

这些边界可能与形状的模型边界
             ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))
             并且如果渲染的内容超出幻灯片原点，它们可能包含负坐标。

视觉边界会考虑渲染相关的方面，例如
             变换（例如旋转）、笔画宽度和连接方式,
             文本布局和溢出、SmartArt 几何以及其他布局效果,
             这些会影响形状最终的渲染外观。

返回的边界不会被裁剪到幻灯片矩形范围内。

### 另请参阅
* 类 [`SmartArtShape`](/slides/python-net/zh/aspose.slides.smartart/smartartshape)
* 类 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)
* 模块 [`aspose.slides.smartart`](/slides/python-net/zh/aspose.slides.smartart)
* 库 [`Aspose.Slides`](/slides/python-net)