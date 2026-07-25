---
title: AddPie()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトで表されるパスに、指定されたパイ形状の輪郭を追加します。
type: docs
weight: 209
url: /ja/system.drawing.drawing2d/graphicspath/addpie/
---
## GraphicsPath::AddPie(float, float, float, float, float, float) メソッド

現在のオブジェクトで表されるパスに、指定されたパイ形状の輪郭を追加します。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | パイが描かれる楕円を囲む矩形の左上隅の X 座標 |
| y | **float** | パイが描かれる楕円を囲む矩形の左上隅の Y 座標 |
| width | **float** | パイが描かれる楕円を囲む矩形の幅 |
| height | **float** | パイが描かれる楕円を囲む矩形の高さ |
| startAngle | **float** | X 軸から時計回りに測定した、パイの開始角度（度）を指定します |
| sweepAngle | **float** | 開始角度からパイの終端までの角度を指定します |

## GraphicsPath::AddPie(int, int, int, int, float, float) メソッド

現在のオブジェクトで表されるパスに、指定されたパイ形状の輪郭を追加します。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(int x, int y, int width, int height, float startAngle, float sweepAngle)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| x | int | パイが描かれる楕円を囲む矩形の左上隅の X 座標 |
| y | int | パイが描かれる楕円を囲む矩形の左上隅の Y 座標 |
| width | int | パイが描かれる楕円を囲む矩形の幅 |
| height | int | パイが描かれる楕円を囲む矩形の高さ |
| startAngle | **float** | X 軸から時計回りに測定した、パイの開始角度（度）を指定します |
| sweepAngle | **float** | 開始角度からパイの終端までの角度を指定します |

## GraphicsPath::AddPie(const Rectangle\&, float, float) メソッド

現在のオブジェクトで表されるパスに、指定されたパイ形状の輪郭を追加します。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(const Rectangle &rect, float startAngle, float sweepAngle)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | パイが描かれる楕円を囲む矩形 |
| startAngle | **float** | X 軸から時計回りに測定した、パイの開始角度（度）を指定します |
| sweepAngle | **float** | 開始角度からパイの終端までの角度を指定します |

## 参照

* クラス [GraphicsPath](../)
* クラス [Rectangle](../../../system.drawing/rectangle/)
* 名前空間 [System::Drawing::Drawing2D](../../)
* ライブラリ [Aspose.Slides](../../../)