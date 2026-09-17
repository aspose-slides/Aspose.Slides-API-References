---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
获取根据渲染内容计算的形状的可视边界。

### 返回

一个 **aspose.slides.RectangleF**，表示形状的可视边界
             以幻灯片坐标表示。



```python
def get_visual_bounds(self):
    ...
```


### 备注

返回的矩形表示所有内容的轴对齐边界
             这些内容由形状在幻灯片坐标空间中的渲染产生。

这些边界可能与形状的模型边界
             ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))
并且如果渲染的内容超出幻灯片原点，可能包含负坐标
             超出幻灯片原点。

可视边界考虑了渲染相关的方面，例如
             变换（例如旋转）、笔画宽度和接合、
             文本布局和溢出、SmartArt 几何形状以及其他布局效果
             这些影响形状最终渲染外观。

返回的边界未被裁剪到幻灯片矩形。



### 另见
* 类 [`Table`](/slides/python-net/zh/aspose.slides/table)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)