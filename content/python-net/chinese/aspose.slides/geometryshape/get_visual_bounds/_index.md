---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
获取根据渲染内容计算得到的形状的可视边界。

### 返回

一个 **aspose.slides.RectangleF**，表示形状在幻灯片坐标中的可视边界
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### 备注

返回的矩形表示在幻灯片坐标空间中形状渲染期间产生的所有内容的轴对齐边界。
            
这些边界可能与形状的模型边界 ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))
并且如果渲染的内容超出幻灯片原点，可能包含负坐标。
            
可视边界会考虑渲染相关的因素，如变换（例如旋转）、笔划宽度和连接、文本布局与溢出、SmartArt 几何形状以及其他影响形状最终渲染外观的布局效果。
            
返回的边界不会被裁剪到幻灯片矩形。



### 另请参见
* 类 [`GeometryShape`](/slides/python-net/zh/aspose.slides/geometryshape)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)