---
title: GraphicsPath()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的填充模式构造 GraphicsPath 类的新实例。
type: docs
weight: 1
url: /zh/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) 构造函数

使用指定的填充模式构造一个新的 [GraphicsPath](../) 类实例。

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | 指定被创建对象所表示的封闭路径的内部应如何填充 |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) 构造函数

构造一个表示指定路径的新的 [GraphicsPath](../) 对象实例。

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | 包含指定由被创建对象表示的路径的点的数组 |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含指定 **pts** 数组中相应点类型的值的数组 |
| fillMode | [FillMode](../../fillmode/) | 指定被创建对象所表示的封闭路径的内部应如何填充 |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) 构造函数

构造一个表示指定路径的新的 [GraphicsPath](../) 对象实例。

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | 包含指定由被创建对象表示的路径的点的数组 |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含指定 **pts** 数组中相应点类型的值的数组 |
| fillMode | [FillMode](../../fillmode/) | 指定被创建对象所表示的封闭路径的内部应如何填充 |

## GraphicsPath::GraphicsPath(const SkPath\&) 构造函数

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## 另请参见

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [GraphicsPath](../)
* Class [Point](../../../system.drawing/point/)
* Class [PointF](../../../system.drawing/pointf/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)