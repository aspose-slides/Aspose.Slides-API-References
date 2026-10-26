---
title: Matrix()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新的 Matrix 类实例，该实例表示单位矩阵。
type: docs
weight: 1
url: /zh/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() 构造函数

构造一个新的 [Matrix](../) 类实例，表示单位矩阵。

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) 构造函数

构造一个新的 [Matrix](../) 类实例，并使用指定的值进行初始化。

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| m11 | **float** | 第1行第1列的值 |
| m12 | **float** | 第1行第2列的值 |
| m21 | **float** | 第2行第1列的值 |
| m22 | **float** | 第2行第2列的值 |
| dx | **float** | 第3行第1列的值 |
| dy | **float** | 第3行第2列的值 |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) 构造函数

构造一个新的 [Matrix](../) 类实例，以由指定矩形和点数组定义的几何变换。

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) 构造函数

构造一个新的 [Matrix](../) 类实例，以由指定矩形和点数组定义的几何变换。

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [Matrix](../)
* 类 [Rectangle](../../../system.drawing/rectangle/)
* 类 [Point](../../../system.drawing/point/)
* 类 [RectangleF](../../../system.drawing/rectanglef/)
* 类 [PointF](../../../system.drawing/pointf/)
* 命名空间 [System::Drawing::Drawing2D](../../)
* 库 [Aspose.Slides](../../../)