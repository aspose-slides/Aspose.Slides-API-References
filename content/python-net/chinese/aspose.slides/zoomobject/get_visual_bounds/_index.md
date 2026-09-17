---
title: get_visual_bounds method
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
获取根据其渲染内容计算的形状的可视边界。

### 返回

一个 **aspose.slides.RectangleF**，表示以幻灯片坐标表示的形状的可视边界。


```python
def get_visual_bounds(self):
    ...
```


### 备注

返回的矩形表示所有内容的轴对齐边界  
produced by the shape during rendering in slide coordinate space.  

这些边界可能与形状的模型边界不同  
([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),  
[`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))  
且如果渲染内容超出幻灯片原点，可能包含负坐标  
beyond the slide origin.  

可视边界考虑了渲染相关的因素，例如  
transformations (for example, rotation), stroke width and joins,  
text layout and overflow, SmartArt geometry, and other layout effects  
that influence the final rendered appearance of the shape.  

返回的边界未被裁剪到幻灯片矩形。



### 另见
* 类 [`ZoomObject`](/slides/python-net/zh/aspose.slides/zoomobject)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)