---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
获取根据渲染内容计算得到的形状的可视边界。

### 返回

一个 **aspose.slides.RectangleF**，表示形状在幻灯片坐标系中的可视边界
             在幻灯片坐标系中。



```python
def get_visual_bounds(self):
    ...
```


### 备注

返回的矩形表示在幻灯片坐标空间中渲染期间由形状产生的所有内容的轴对齐边界。
             
这些边界可能与形状的模型边界
             ([`Shape.x`](/slides/python-net/zh/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh/aspose.slides/shape/height))
             不同，并且如果渲染内容超出幻灯片原点，则可能包含负坐标。
             
可视边界会考虑渲染相关的方面，例如
             变换（例如，旋转），笔画宽度和连接，
             文本布局和溢出，SmartArt 几何形状，以及其他布局效果
             影响形状的最终渲染外观。
             
返回的边界未被裁剪到幻灯片矩形内。



### 另请参见
* 类 [`PictureFrame`](/slides/python-net/zh/aspose.slides/pictureframe)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)