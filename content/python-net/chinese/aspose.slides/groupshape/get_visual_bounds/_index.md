---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
获取形状的可视边界，该边界根据其渲染内容计算得出。

### 返回
一个 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)，表示形状在幻灯片坐标系中的可视边界。

```python
def get_visual_bounds(self):
    ...
```

### 备注
返回的矩形表示所有内容的轴对齐边界
             由形状在幻灯片坐标空间中的渲染期间生成的。

这些边界可能不同于形状的模型边界
             ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))
             并且如果渲染的内容扩展
             超出幻灯片原点，则可能包含负坐标。

可视边界考虑了与渲染相关的方面，例如
             转换（例如，旋转），笔划宽度和接合，
             文本布局和溢出，SmartArt 几何形状，以及影响形状最终渲染外观的其他布局效果

返回的边界不会被裁剪到幻灯片矩形内。

### 另请参阅
* 类 [`GroupShape`](/slides/python-net/zh/aspose.slides/groupshape)
* 类 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)