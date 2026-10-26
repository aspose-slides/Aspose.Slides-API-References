---
title: FillClosedCurve()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたブラシを使用して閉じたスプラインを描画します。
type: docs
weight: 807
url: /ja/system.drawing/graphics/fillclosedcurve/
---
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) method

指定されたブラシを使用して閉じたスプラインを描画します。

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | スプラインを描画する際に使用するブラシ |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) のポイントでスプラインを決定します |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 無視 |
| tension | **float** | スプラインのテンションを指定する値 |

## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) method

指定されたブラシを使用して閉じたスプラインを描画します。

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | スプラインを描画する際に使用するブラシ |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) のポイントでスプラインを決定します |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 無視 |
| tension | **float** | スプラインのテンションを指定する値 |

## 参照

* 列挙型 [FillMode](../../../system.drawing.drawing2d/fillmode/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [Brush](../../brush/)
* クラス [PointF](../../pointf/)
* クラス [Graphics](../)
* クラス [Point](../../point/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)