---
title: DrawLine()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたペンを使用して指定された線を描画します。
type: docs
weight: 456
url: /ja/system.drawing/graphics/drawline/
---
## Graphics::DrawLine(const SharedPtr\<Pen\>\&, Point, Point) method

指定されたペンを使用して指定された線を描画します。

```cpp
void System::Drawing::Graphics::DrawLine(const SharedPtr<Pen> &pen, Point pt1, Point pt2)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | [Pen](../../pen/) オブジェクトで、描画する線のグラフィック属性を指定します |
| pt1 | [Point](../../point/) | 描画する線を定義する最初の点 |
| pt2 | [Point](../../point/) | 描画する線を定義する2番目の点 |

## Graphics::DrawLine(const SharedPtr\<Pen\>\&, PointF, PointF) method

指定されたペンを使用して指定された線を描画します。

```cpp
void System::Drawing::Graphics::DrawLine(const SharedPtr<Pen> &pen, PointF pt1, PointF pt2)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | [Pen](../../pen/) オブジェクトで、描画する線のグラフィック属性を指定します |
| pt1 | [PointF](../../pointf/) | 描画する線を定義する最初の点 |
| pt2 | [PointF](../../pointf/) | 描画する線を定義する2番目の点 |

## Graphics::DrawLine(const SharedPtr\<Pen\>\&, int, int, int, int) method

指定されたペンを使用して指定された線を描画します。

```cpp
void System::Drawing::Graphics::DrawLine(const SharedPtr<Pen> &pen, int x1, int y1, int x2, int y2)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | [Pen](../../pen/) オブジェクトで、描画する線のグラフィック属性を指定します |
| x1 | int | 描画する線を定義する最初の点のX座標 |
| y1 | int | 描画する線を定義する最初の点のY座標 |
| x2 | int | 描画する線を定義する2番目の点のX座標 |
| y2 | int | 描画する線を定義する2番目の点のY座標 |

## Graphics::DrawLine(const SharedPtr\<Pen\>\&, float, float, float, float) method

指定されたペンを使用して指定された線を描画します。

```cpp
void System::Drawing::Graphics::DrawLine(const SharedPtr<Pen> &pen, float x1, float y1, float x2, float y2)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | [Pen](../../pen/) オブジェクトで、描画する線のグラフィック属性を指定します |
| x1 | **float** | 描画する線を定義する最初の点のX座標 |
| y1 | **float** | 描画する線を定義する最初の点のY座標 |
| x2 | **float** | 描画する線を定義する2番目の点のX座標 |
| y2 | **float** | 描画する線を定義する2番目の点のY座標 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)