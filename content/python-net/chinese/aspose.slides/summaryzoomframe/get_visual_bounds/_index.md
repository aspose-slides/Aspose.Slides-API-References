---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
获取根据已渲染内容计算的形状的可视边界。

### 返回值

一个 **aspose.slides.RectangleF**，表示形状在幻灯片坐标中的可视边界
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### 备注

返回的矩形表示所有内容的轴对齐边界
             produced by the shape during rendering in slide coordinate space.
            
这些边界可能与形状的模型边界
             ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))
并且如果渲染的内容超出幻灯片原点，可能包含负坐标
             beyond the slide origin.
            
可视边界会考虑渲染相关的因素，例如变换（例如旋转）、笔画宽度和连接、文本布局与溢出、SmartArt 几何形状以及其他影响形状最终渲染外观的布局效果
             such as transformations (for example, rotation), stroke width and joins,
             text layout and overflow, SmartArt geometry, and other layout effects
             that influence the final rendered appearance of the shape.
            
返回的边界未被裁剪到幻灯片矩形。
             are not clipped to the slide rectangle.



### 参见
* 类 [`SummaryZoomFrame`](/slides/python-net/zh/aspose.slides/summaryzoomframe)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)