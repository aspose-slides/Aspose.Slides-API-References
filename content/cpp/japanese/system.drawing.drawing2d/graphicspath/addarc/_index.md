---
title: AddArc()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトで表されるパスに、指定された楕円弧を追加します。
type: docs
weight: 183
url: /ja/system.drawing.drawing2d/graphicspath/addarc/
---
## GraphicsPath::AddArc(float, float, float, float, float, float) メソッド

現在のオブジェクトで表されるパスに、指定された楕円弧を追加します。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 弧が描かれる楕円を囲む矩形の左上隅の X 座標 |
| y | **float** | 弧が描かれる楕円を囲む矩形の左上隅の Y 座標 |
| width | **float** | 弧が描かれる楕円を囲む矩形の幅 |
| height | **float** | 弧が描かれる楕円を囲む矩形の高さ |
| startAngle | **float** | X 軸から時計回りに測定した、度単位の弧の開始角度を指定します。 |
| sweepAngle | **float** | 開始角度から弧の終点までの角度を指定します。 |

## GraphicsPath::AddArc(int, int, int, int, float, float) メソッド

現在のオブジェクトで表されるパスに、指定された楕円弧を追加します。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(int x, int y, int width, int height, float startAngle, float sweepAngle)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | 弧が描かれる楕円を囲む矩形の左上隅の X 座標 |
| y | int | 弧が描かれる楕円を囲む矩形の左上隅の Y 座標 |
| width | int | 弧が描かれる楕円を囲む矩形の幅 |
| height | int | 弧が描かれる楕円を囲む矩形の高さ |
| startAngle | **float** | X 軸から時計回りに測定した、度単位の弧の開始角度を指定します。 |
| sweepAngle | **float** | 開始角度から弧の終点までの角度を指定します。 |

## GraphicsPath::AddArc(const RectangleF\&, float, float) メソッド

現在のオブジェクトで表されるパスに、指定された楕円弧を追加します。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const RectangleF &rect, float startAngle, float sweepAngle)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | const [RectangleF](../../../system.drawing/rectanglef/)\& | 弧が描かれる楕円を囲む矩形 |
| startAngle | **float** | X 軸から時計回りに測定した、度単位の弧の開始角度を指定します。 |
| sweepAngle | **float** | 開始角度から弧の終点までの角度を指定します。 |

## GraphicsPath::AddArc(const Rectangle\&, float, float) メソッド

現在のオブジェクトで表されるパスに、指定された楕円弧を追加します。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const Rectangle &rect, float startAngle, float sweepAngle)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | 弧が描かれる楕円を囲む矩形 |
| startAngle | **float** | X 軸から時計回りに測定した、度単位の弧の開始角度を指定します。 |
| sweepAngle | **float** | 開始角度から弧の終点までの角度を指定します。 |

## 参照

* クラス [GraphicsPath](../)
* クラス [RectangleF](../../../system.drawing/rectanglef/)
* クラス [Rectangle](../../../system.drawing/rectangle/)
* 名前空間 [System::Drawing::Drawing2D](../../)
* ライブラリ [Aspose.Slides](../../../)