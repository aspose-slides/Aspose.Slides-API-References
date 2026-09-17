---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
获取形状的可视边界，该边界根据其渲染内容计算得到。

### 返回

一个 **aspose.slides.RectangleF**，表示形状的可视边界
             在幻灯片坐标中。



```python
def get_visual_bounds(self):
    ...
```


### 备注

返回的矩形表示所有内容的轴对齐边界
             该内容由形状在幻灯片坐标空间的渲染期间产生。
             
             这些边界可能与形状的模型边界不同
             ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))
             并且如果渲染的内容扩展
             超出幻灯片原点时，可能包含负坐标。
             
             可视边界考虑了渲染相关的方面，例如
             变换（例如，旋转），笔画宽度和接合，
             文本布局和溢出，SmartArt 几何，以及其他布局效果
             这些影响形状的最终渲染外观。
             
             返回的边界未被裁剪到幻灯片矩形。



### 另请参见
* 类 [`GroupShape`](/slides/python-net/zh/aspose.slides/groupshape)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)