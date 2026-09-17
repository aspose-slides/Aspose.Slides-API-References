---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
获取形状从其渲染内容计算得出的可视边界。

### 返回值

一个 **aspose.slides.RectangleF**，表示形状在幻灯片坐标系中的可视边界


```python
def get_visual_bounds(self):
    ...
```


### 备注
The returned rectangle represents the axis-aligned bounds of all content
             produced by the shape during rendering in slide coordinate space.

             These bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))
             and may contain negative coordinates if the rendered content extends
             beyond the slide origin.

             The visual bounds take into account rendering-related aspects such as
             transformations (for example, rotation), stroke width and joins,
             text layout and overflow, SmartArt geometry, and other layout effects
             that influence the final rendered appearance of the shape.

             The returned bounds are not clipped to the slide rectangle.

### 另见
* 类 [`AutoShape`](/slides/python-net/zh/aspose.slides/autoshape)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)