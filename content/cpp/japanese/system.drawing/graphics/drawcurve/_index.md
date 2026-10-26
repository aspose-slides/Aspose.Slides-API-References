---
title: DrawCurve()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたペンを使用してスプラインを描画します。
type: docs
weight: 794
url: /ja/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) メソッド

指定されたペンを使用してスプラインを描画します。

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | スプラインを描画する際に使用するペン |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) のポイントでスプラインを決定します |
| tension | **float** | スプラインの張力を指定する値 |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) メソッド

指定されたペンを使用してスプラインを描画します。

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | スプラインを描画する際に使用するペン |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) のポイントでスプラインを決定します |
| tension | **float** | スプラインの張力を指定する値 |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) メソッド

指定されたペンを使用してスプラインを描画します。

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | スプラインを描画する際に使用するペン |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) のポイントでスプラインを決定します |
| offset | **int32_t** | **points** 配列の最初の要素からのオフセット |
| numberOfSegments | **int32_t** | 曲線に含めるセグメント数 |
| tension | **float** | スプラインの張力を指定する値 |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) メソッド

指定されたペンを使用してスプラインを描画します。

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | スプラインを描画する際に使用するペン |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) のポイントでスプラインを決定します |
| offset | **int32_t** | **points** 配列の最初の要素からのオフセット |
| numberOfSegments | **int32_t** | 曲線に含めるセグメント数 |
| tension | **float** | スプラインの張力を指定する値 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [Pen](../../pen/)
* クラス [Point](../../point/)
* クラス [Graphics](../)
* クラス [PointF](../../pointf/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)