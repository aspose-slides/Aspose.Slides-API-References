---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
获取从渲染内容计算得到的形状的可视边界。

### Returns

一个 **aspose.slides.RectangleF**，表示形状的可视边界
             在幻灯片坐标中。



```python
def get_visual_bounds(self):
    ...
```


### Remarks

返回的矩形表示所有内容的轴对齐边界
             由形状在幻灯片坐标空间渲染期间产生。

             
             这些边界可能与形状的模型边界
             ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))
             并且如果渲染的内容扩展到
             幻灯片原点之外。

             
             可视边界考虑了渲染相关的因素，例如
             变换（例如旋转）、笔划宽度和连接，
             文本布局和溢出、SmartArt 几何形状，以及其他布局效果
             这些影响形状最终渲染外观。

             
             返回的边界未裁剪到幻灯片矩形。



### See Also
* 类 [`ZoomFrame`](/slides/python-net/zh/aspose.slides/zoomframe)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)