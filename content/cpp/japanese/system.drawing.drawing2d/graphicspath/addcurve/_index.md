---
title: AddCurve()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すパスに、指定された曲線を追加します。
type: docs
weight: 274
url: /ja/system.drawing.drawing2d/graphicspath/addcurve/
---
## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, float) method

指定された曲線を、現在のオブジェクトが表すパスに追加します。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, float tension=0.5)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | 曲線を指定するポイント |
| tension | **float** | 制御点間で曲線がどれだけ曲がるかを指定します。 |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, float) method

指定された曲線を、現在のオブジェクトが表すパスに追加します。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, float tension=0.5)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | 曲線を指定するポイント |
| tension | **float** | 制御点間で曲線がどれだけ曲がるかを指定します。 |

## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, int, int, float) method

指定された曲線を、現在のオブジェクトが表すパスに追加します。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, int offset, int number_of_segments, float tension)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | 曲線を指定するポイント |
| offset | int | 曲線の開始点として使用される **points** 内の点のインデックス |
| number_of_segments | int | 曲線の描画に使用されるセグメントの数 |
| tension | **float** | 制御点間で曲線がどれだけ曲がるかを指定します。 |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, int, int, float) method

指定された曲線を、現在のオブジェクトが表すパスに追加します。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, int offset, int number_of_segments, float tension)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | 曲線を指定するポイント |
| offset | int | 曲線の開始点として使用される **points** 内の点のインデックス |
| number_of_segments | int | 曲線の描画に使用されるセグメントの数 |
| tension | **float** | 制御点間で曲線がどれだけ曲がるかを指定します。 |

## 参照

* typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [PointF](../../../system.drawing/pointf/)
* クラス [GraphicsPath](../)
* クラス [Point](../../../system.drawing/point/)
* 名前空間 [System::Drawing::Drawing2D](../../)
* ライブラリ [Aspose.Slides](../../../)