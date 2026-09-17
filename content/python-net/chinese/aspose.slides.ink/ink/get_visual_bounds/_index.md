---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
获取形状的可视边界（根据其渲染内容计算）。

### 返回

一个 **aspose.slides.RectangleF**，表示形状
             在幻灯片坐标中的可视边界。

```python
def get_visual_bounds(self):
    ...
```

### 备注
返回的矩形表示所有内容的轴对齐边界
             由形状在幻灯片坐标空间中渲染期间产生。

这些边界可能与形状的模型边界不同
             ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))
             并且如果渲染的内容超出幻灯片原点，可能包含负坐标。

可视边界考虑了渲染相关的因素，例如
             变换（例如，旋转）、笔画宽度和连接、
             文本布局和溢出、SmartArt 几何以及其他
             影响形状最终渲染外观的布局效果。

返回的边界不会被裁剪到幻灯片矩形。

### 另见
* 类 [`Ink`](/slides/python-net/zh/aspose.slides.ink/ink)
* 模块 [`aspose.slides.ink`](/slides/python-net/zh/aspose.slides.ink)
* 库 [`Aspose.Slides`](/slides/python-net)