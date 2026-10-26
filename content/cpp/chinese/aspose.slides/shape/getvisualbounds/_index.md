---
title: GetVisualBounds()
second_title: Aspose.Slides for C++ API 参考
description: 获取根据已渲染内容计算的形状的可视边界。
type: docs
weight: 677
url: /zh/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() 方法

获取根据其渲染内容计算得到的形状的可视边界。

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```

### 返回值

一个 [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)，表示幻灯片坐标系中形状的可视边界。

## 备注

返回的矩形表示在幻灯片坐标空间中渲染期间形状生成的所有内容的轴对齐边界。

这些边界可能与形状的模型边界（[Shape::X](../)，[Shape::Y](../)，[Shape::Width](../)，[Shape::Height](../)）不同，并且如果渲染内容超出幻灯片原点，则可能包含负坐标。

可视边界考虑了渲染相关的因素，例如变换（例如旋转）、笔画宽度和连接、文本布局和溢出、[SmartArt](../../../aspose.slides.smartart/) 几何形状以及其他影响形状最终渲染外观的布局效果。

返回的边界未被裁剪到幻灯片矩形。

## 参见

* 类 [RectangleF](../../../system.drawing/rectanglef/)
* 类 [Shape](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)