---
title: FillPie()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す表面上で、指定されたブラシを使用して指定されたパイを塗りつぶします。
type: docs
weight: 274
url: /ja/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) メソッド

指定されたブラシを使用して、現在のオブジェクトが表す表面上に指定されたパイを塗りつぶします。

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | パイを塗りつぶす際に使用するブラシ |
| x | int | 楕円を定義する矩形の左上隅の X 座標 |
| y | int | 楕円を定義する矩形の左上隅の Y 座標 |
| width | int | 楕円を定義する矩形の幅 |
| height | int | 楕円を定義する矩形の高さ |
| startAngle | int | X 軸から時計回りに測定したパイの開始点までの角度（度） |
| sweepAngle | int | **startAngle** から時計回りに測定したパイの終了点までの角度（度） |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) メソッド

指定されたブラシを使用して、現在のオブジェクトが表す表面上に指定されたパイを塗りつぶします。

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | パイを塗りつぶす際に使用するブラシ |
| x | **float** | 楕円を定義する矩形の左上隅の X 座標 |
| y | **float** | 楕円を定義する矩形の左上隅の Y 座標 |
| width | **float** | 楕円を定義する矩形の幅 |
| height | **float** | 楕円を定義する矩形の高さ |
| startAngle | **float** | X 軸から時計回りに測定したパイの開始点までの角度（度） |
| sweepAngle | **float** | **startAngle** から時計回りに測定したパイの終了点までの角度（度） |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) メソッド

指定されたブラシを使用して、現在のオブジェクトが表す表面上に指定されたパイを塗りつぶします。

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | パイを塗りつぶす際に使用するブラシ |
| rect | [Rectangle](../../rectangle/) | 楕円を定義する矩形 |
| startAngle | **float** | X 軸から時計回りに測定したパイの開始点までの角度（度） |
| sweepAngle | **float** | **startAngle** から時計回りに測定したパイの終了点までの角度（度） |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Brush](../../brush/)
* クラス [Graphics](../)
* クラス [Rectangle](../../rectangle/)
* 名前空間 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)