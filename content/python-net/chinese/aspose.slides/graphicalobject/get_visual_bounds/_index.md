---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
获取形状的可视边界，该边界根据其渲染内容计算得到。

### 返回
一个 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)，表示形状的可视边界
             在幻灯片坐标系中。

```python
def get_visual_bounds(self):
    ...
```

### 备注
返回的矩形表示所有内容的轴对齐边界
             由形状在幻灯片坐标空间渲染期间产生的内容。

这些边界可能与形状的模型边界不同
             ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))
             并且如果渲染的内容扩展，可能包含负坐标
             超出幻灯片原点。

可视边界考虑了与渲染相关的方面，例如
             变换（例如旋转）、笔画宽度和连接，
             文本布局和溢出、SmartArt 几何以及其他布局效果
             这些会影响形状最终的渲染外观。

返回的边界未被裁剪到幻灯片矩形。

### 参见
* 类 [`GraphicalObject`](/slides/python-net/zh/aspose.slides/graphicalobject)
* 类 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)