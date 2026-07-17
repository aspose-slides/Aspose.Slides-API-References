---
title: PathGradientBrush()
second_title: Aspose.Slides C++ API 参考
description: 构造 PathGradientBrush 类的新实例。
type: docs
weight: 1
url: /zh/system.drawing.drawing2d/pathgradientbrush/pathgradientbrush/
---
## PathGradientBrush::PathGradientBrush(const ArrayPtr\<PointF\>\&, WrapMode) 构造函数

构造 [PathGradientBrush](../) 类的新实例。

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const ArrayPtr<PointF> &points, WrapMode wrapMode=WrapMode::Clamp)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | 包含路径顶点的数组 |
| wrapMode | [WrapMode](../../wrapmode/) | 指定由正在创建的对象表示的画笔绘制的填充应如何平铺 |

## PathGradientBrush::PathGradientBrush(const ArrayPtr\<Point\>\&, WrapMode) 构造函数

构造 [PathGradientBrush](../) 类的新实例。

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const ArrayPtr<Point> &points, WrapMode wrapMode=WrapMode::Clamp)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | 包含路径顶点的数组 |
| wrapMode | [WrapMode](../../wrapmode/) | 指定由正在创建的对象表示的画笔绘制的填充应如何平铺 |

## PathGradientBrush::PathGradientBrush(const SharedPtr\<GraphicsPath\>\&) 构造函数

构造 [PathGradientBrush](../) 类的新实例。

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const SharedPtr<GraphicsPath> &path)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | 指定由正在创建的对象填充的路径的 [GraphicsPath](../../graphicspath/) 对象 |

## 另请参见

* 枚举 [WrapMode](../../wrapmode/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [PointF](../../../system.drawing/pointf/)
* 类 [PathGradientBrush](../)
* 类 [Point](../../../system.drawing/point/)
* 类 [GraphicsPath](../../graphicspath/)
* 命名空间 [System::Drawing::Drawing2D](../../)
* 库 [Aspose.Slides](../../../)