---
title: DrawPie()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すサーフェス上で、指定されたペンを使用して指定されたパイを描画します。
type: docs
weight: 261
url: /ja/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) method

現在のオブジェクトが表すサーフェス上に、指定されたペンを使用して指定されたパイを描画します。

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | パイの描画に使用するペン |
| x | **int32_t** | 楕円を定義する矩形の左上隅の X 座標 |
| y | **int32_t** | 楕円を定義する矩形の左上隅の Y 座標 |
| width | **int32_t** | 楕円を定義する矩形の幅 |
| height | **int32_t** | 楕円を定義する矩形の高さ |
| startAngle | **int32_t** | X 軸から時計回りに測定した、パイの開始点までの角度（度） |
| sweepAngle | **int32_t** | **startAngle** から時計回りに測定した、パイの終了点までの角度（度） |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) method

現在のオブジェクトが表すサーフェス上に、指定されたペンを使用して指定されたパイを描画します。

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | パイの描画に使用するペン |
| x | **float** | 楕円を定義する矩形の左上隅の X 座標 |
| y | **float** | 楕円を定義する矩形の左上隅の Y 座標 |
| width | **float** | 楕円を定義する矩形の幅 |
| height | **float** | 楕円を定義する矩形の高さ |
| startAngle | **float** | X 軸から時計回りに測定した、パイの開始点までの角度（度） |
| sweepAngle | **float** | **startAngle** から時計回りに測定した、パイの終了点までの角度（度） |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) method

現在のオブジェクトが表すサーフェス上に、指定されたペンを使用して指定されたパイを描画します。

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | パイの描画に使用するペン |
| rect | [Rectangle](../../rectangle/) | 楕円を定義する矩形 |
| startAngle | **float** | X 軸から時計回りに測定した、パイの開始点までの角度（度） |
| sweepAngle | **float** | **startAngle** から時計回りに測定した、パイの終了点までの角度（度） |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) method

現在のオブジェクトが表すサーフェス上に、指定されたペンを使用して指定されたパイを描画します。

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | パイの描画に使用するペン |
| rect | [RectangleF](../../rectanglef/) | 楕円を定義する矩形 |
| startAngle | **float** | X 軸から時計回りに測定した、パイの開始点までの角度（度） |
| sweepAngle | **float** | **startAngle** から時計回りに測定した、パイの終了点までの角度（度） |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Pen](../../pen/)
* クラス [Graphics](../)
* クラス [Rectangle](../../rectangle/)
* クラス [RectangleF](../../rectanglef/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)