---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
获取根据渲染内容计算的形状的可视边界。

### 返回值

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### 备注
返回的矩形表示所有内容的轴对齐边界
            由形状在渲染期间产生的

            这些边界可能与形状的模型边界不同
            ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
            [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))
            并且如果渲染的内容超出
            幻灯片原点，可能包含负坐标。

            可视边界考虑了与渲染相关的因素，例如
            变换（例如旋转）、笔画宽度和接合，
            文本布局和溢出、SmartArt 几何以及其他布局效果
            影响形状最终渲染外观的因素。

            返回的边界未被裁剪到幻灯片矩形。

### 另请参见
* 类 [`SectionZoomFrame`](/slides/python-net/zh/aspose.slides/sectionzoomframe)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)