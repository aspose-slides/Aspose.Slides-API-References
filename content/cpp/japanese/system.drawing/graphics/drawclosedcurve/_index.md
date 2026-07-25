---
title: DrawClosedCurve()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたペンを使用して閉じたスプラインを描画します。
type: docs
weight: 781
url: /ja/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) メソッド

指定されたペンを使用して閉じたスプラインを描画します。

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | スプラインを描く際に使用するペン |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) スプラインを決定する点 |
| tension | **float** | スプラインの張力を指定する値 |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 無視されます |

## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) メソッド

指定されたペンを使用して閉じたスプラインを描画します。

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | スプラインを描く際に使用するペン |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) スプラインを決定する点 |
| tension | **float** | スプラインの張力を指定する値 |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 無視されます |

## 参照

* 列挙型 [FillMode](../../../system.drawing.drawing2d/fillmode/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [Pen](../../pen/)
* クラス [Point](../../point/)
* クラス [Graphics](../)
* クラス [PointF](../../pointf/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)