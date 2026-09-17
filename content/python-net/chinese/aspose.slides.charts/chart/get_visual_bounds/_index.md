---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
获取形状从其渲染内容计算得到的可视边界。

### 返回
一个 **aspose.slides.RectangleF** 表示形状的可视边界
             在幻灯片坐标中。

```python
def get_visual_bounds(self):
    ...
```

### 备注
返回的矩形表示所有内容的轴对齐边界
             由形状在幻灯片坐标空间中渲染期间产生的内容。

             这些边界可能与形状的模型边界不同
             ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))
             并且如果渲染内容超出幻灯片原点，可能包含负坐标。

             可视边界会考虑渲染相关的方面，例如
             变换（例如，旋转）、笔画宽度和连接、
             文本布局和溢出、SmartArt 几何形状以及其他布局效果，
             这些会影响形状最终的渲染外观。

             返回的边界不会被裁剪到幻灯片矩形。

### 另见
* 类 [`Chart`](/slides/python-net/zh/aspose.slides.charts/chart)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)