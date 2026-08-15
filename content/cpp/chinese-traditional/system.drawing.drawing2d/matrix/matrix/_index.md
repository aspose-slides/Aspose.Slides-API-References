---
title: Matrix()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個代表單位矩陣的 Matrix 類別的新實例。
type: docs
weight: 1
url: /zh-hant/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() 建構函式

建立一個 [Matrix](../) 類別的新實例，該實例代表單位矩陣。

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) 建構函式

建立一個 [Matrix](../) 類別的新實例，並使用指定的值進行初始化。

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| m11 | **float** | 第1行第1列的值 |
| m12 | **float** | 第1行第2列的值 |
| m21 | **float** | 第2行第1列的值 |
| m22 | **float** | 第2行第2列的值 |
| dx | **float** | 第3行第1列的值 |
| dy | **float** | 第3行第2列的值 |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) 建構函式

建立 [Matrix](../) 類別的新實例，以指定的矩形和點陣列所定義的幾何變換。

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) 建構函式

建立 [Matrix](../) 類別的新實例，以指定的矩形和點陣列所定義的幾何變換。

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## 參見

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [Matrix](../)
* 類別 [Rectangle](../../../system.drawing/rectangle/)
* 類別 [Point](../../../system.drawing/point/)
* 類別 [RectangleF](../../../system.drawing/rectanglef/)
* 類別 [PointF](../../../system.drawing/pointf/)
* 命名空間 [System::Drawing::Drawing2D](../../)
* 函式庫 [Aspose.Slides](../../../)