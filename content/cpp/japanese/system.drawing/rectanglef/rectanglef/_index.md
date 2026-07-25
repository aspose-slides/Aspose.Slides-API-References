---
title: RectangleF()
second_title: Aspose.Slides for C++ API リファレンス
description: X と Y の座標、および幅と高さの値が 0 に設定された矩形を表す RectangleF オブジェクトの新しいインスタンスを構築します。
type: docs
weight: 1
url: /ja/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() constructor

X と Y の座標、および幅と高さの値が 0 に設定された矩形を表す [RectangleF](../) オブジェクトの新しいインスタンスを構築します。

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) constructor

左上隅の指定された座標と幅と高さを持つ矩形を表す [RectangleF](../) オブジェクトの新しいインスタンスを構築します。

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 矩形の左上隅の X 座標の値 |
| y | **float** | 矩形の左上隅の Y 座標の値 |
| width | **float** | 矩形の幅 |
| height | **float** | 矩形の高さ |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) constructor

[PointF](../../pointf/) クラスのインスタンスとして指定された左上隅の座標と、[SizeF](../../sizef/) クラスのインスタンスとして指定された幅と高さを持つ矩形を表す [RectangleF](../) オブジェクトの新しいインスタンスを構築します。

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | 矩形の左上隅の位置を指定します |
| size | const [SizeF](../../sizef/)\& | 矩形の幅と高さを指定します |

## RectangleF::RectangleF(const Rectangle\&) constructor

指定された矩形と等価な矩形を表す [RectangleF](../) オブジェクトの新しいインスタンスを構築します。

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 構築されるオブジェクトが表す矩形の位置とサイズを指定する [Rectangle](../../rectangle/) クラスのインスタンス |

## 参照

* クラス [RectangleF](../)
* クラス [PointF](../../pointf/)
* クラス [SizeF](../../sizef/)
* クラス [Rectangle](../../rectangle/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)