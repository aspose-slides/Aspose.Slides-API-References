---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
获取从渲染内容计算得到的形状的可视边界。

### 返回
一个 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)，表示形状在幻灯片坐标系中的可视边界
             。

```python
def get_visual_bounds(self):
    ...
```

### 备注
返回的矩形表示在幻灯片坐标空间中渲染期间形状产生的所有内容的轴对齐边界。

这些边界可能与形状的模型边界（[`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height)）不同，如果渲染内容超出幻灯片原点，还可能包含负坐标。

可视边界考虑了渲染相关的方面，例如变换（例如旋转）、笔画宽度和连接、文本布局和溢出、SmartArt 几何形状以及其他影响形状最终渲染外观的布局效果。

返回的边界不会被裁剪到幻灯片矩形。

### 另见
* 类 [`SummaryZoomFrame`](/slides/python-net/zh/aspose.slides/summaryzoomframe)
* 类 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)