---
title: Matrix()
second_title: Aspose.Slides for C++ API リファレンス
description: 単位行列を表す Matrix クラスの新しいインスタンスを作成します。
type: docs
weight: 1
url: /ja/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() コンストラクタ

[Matrix](../) クラスの新しいインスタンスを作成し、単位行列を表します。

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) コンストラクタ

[Matrix](../) クラスの新しいインスタンスを作成し、指定された値で初期化します。

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| m11 | **float** | 1行目 1列目の値 |
| m12 | **float** | 1行目 2列目の値 |
| m21 | **float** | 2行目 1列目の値 |
| m22 | **float** | 2行目 2列目の値 |
| dx | **float** | 3行目 1列目の値 |
| dy | **float** | 3行目 2列目の値 |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) コンストラクタ

指定された矩形とポイント配列で定義された幾何変換に対して、[Matrix](../) クラスの新しいインスタンスを作成します。

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) コンストラクタ

指定された矩形とポイント配列で定義された幾何変換に対して、[Matrix](../) クラスの新しいインスタンスを作成します。

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Matrix](../)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [Point](../../../system.drawing/point/)
* Class [RectangleF](../../../system.drawing/rectanglef/)
* Class [PointF](../../../system.drawing/pointf/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)