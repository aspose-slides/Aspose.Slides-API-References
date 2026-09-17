---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
获取形状从其渲染内容计算得到的视觉边界。

### 返回

一个 **aspose.slides.RectangleF**，表示形状在幻灯片坐标中的视觉边界。

```python
def get_visual_bounds(self):
    ...
```

### 备注

返回的矩形表示在幻灯片坐标空间中渲染时形状生成的所有内容的轴对齐边界。

这些边界可能与形状的模型边界 ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height)) 不同，且如果渲染的内容超出幻灯片原点，可能包含负坐标。

视觉边界会考虑渲染相关的因素，例如变换（例如旋转）、描边宽度和连接、文本布局与溢出、SmartArt 几何形状以及其他影响形状最终渲染外观的布局效果。

返回的边界不会被裁剪到幻灯片矩形内。

### 参见
* 类 [`SmartArt`](/slides/python-net/zh/aspose.slides.smartart/smartart)
* 模块 [`aspose.slides.smartart`](/slides/python-net/zh/aspose.slides.smartart)
* 库 [`Aspose.Slides`](/slides/python-net)