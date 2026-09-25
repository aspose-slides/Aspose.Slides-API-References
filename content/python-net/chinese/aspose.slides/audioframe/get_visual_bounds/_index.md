---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
获取形状的可视边界，该边界基于其渲染内容计算。

### 返回值

一个 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)，表示形状在幻灯片坐标中的可视边界
             。

```python
def get_visual_bounds(self):
    ...
```

### 备注

返回的矩形表示所有内容的轴对齐边界
             该内容由形状在幻灯片坐标空间中渲染期间生成。

这些边界可能与形状的模型边界不同
             ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))
             并且如果渲染的内容超出幻灯片原点，可能包含负坐标。

可视边界会考虑渲染相关的因素，例如
             变换（例如旋转）、描边宽度和连接方式、
             文本布局与溢出、SmartArt 几何形状，以及影响形状最终渲染外观的其他布局效果。

返回的边界未被裁剪到幻灯片矩形。

### 另见
* 类 [`AudioFrame`](/slides/python-net/zh/aspose.slides/audioframe)
* 类 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)