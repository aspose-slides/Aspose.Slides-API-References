---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
获取形状的视觉边界，该边界是根据其渲染内容计算得出的。

### 返回值

一个 **aspose.slides.RectangleF**，表示形状在幻灯片坐标系中的视觉边界。

```python
def get_visual_bounds(self):
    ...
```

### 备注

返回的矩形表示在幻灯片坐标空间中渲染期间由形状产生的所有内容的轴对齐边界。

这些边界可能与形状的模型边界 ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height)) 不同，并且如果渲染的内容超出幻灯片原点，可能包含负坐标。

视觉边界考虑了渲染相关的因素，例如变换（例如旋转）、笔画宽度和接合、文本布局与溢出、SmartArt 几何形状以及其他影响形状最终渲染外观的布局效果。

返回的边界不会被裁剪到幻灯片矩形内。

### 另请参阅
* 类 [`AudioFrame`](/slides/python-net/zh/aspose.slides/audioframe)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)