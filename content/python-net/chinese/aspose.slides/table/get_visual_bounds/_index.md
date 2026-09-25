---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
获取形状的视觉边界，该边界是根据其渲染内容计算的。

### 返回值

一个 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)，表示形状
             在幻灯片坐标中的视觉边界。



```python
def get_visual_bounds(self):
    ...
```


### 备注

返回的矩形表示在幻灯片坐标空间中渲染期间由形状生成的所有内容的轴对齐边界。
            
这些边界可能不同于形状的模型边界
             ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))，如果渲染内容超出幻灯片原点，可能包含负坐标。
            
视觉边界考虑了渲染相关的因素，例如变换（如旋转）、笔画宽度和连接、文本布局和溢出、SmartArt 几何形状以及其他影响形状最终渲染外观的布局效果。
            
返回的边界未被裁剪至幻灯片矩形。



### 另请参见
* 类 [`Table`](/slides/python-net/zh/aspose.slides/table)
* 类 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)