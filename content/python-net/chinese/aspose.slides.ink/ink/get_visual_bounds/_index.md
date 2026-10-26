---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
获取形状的视觉边界，该边界是根据其渲染内容计算得出的。

### 返回

一个 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef) 表示形状的视觉边界
在幻灯片坐标系中。

```python
def get_visual_bounds(self):
    ...
```

### 备注

返回的矩形表示所有内容的轴对齐边界
由形状在幻灯片坐标空间中渲染期间产生的内容。

这些边界可能与形状的模型边界
([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))
不同，并且如果渲染的内容扩展超出幻灯片原点，可能包含负坐标。

视觉边界考虑了与渲染相关的方面，例如
变换（例如，旋转）、笔画宽度和连接，
文本布局和溢出、SmartArt 几何以及其他布局效果，
这些因素会影响形状最终的渲染外观。

返回的边界未被裁剪到幻灯片矩形。

### 另请参见
* 类 [`Ink`](/slides/python-net/zh/aspose.slides.ink/ink)
* 类 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)
* 模块 [`aspose.slides.ink`](/slides/python-net/zh/aspose.slides.ink)
* 库 [`Aspose.Slides`](/slides/python-net)