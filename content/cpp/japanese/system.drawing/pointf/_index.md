---
title: PointF
second_title: Aspose.Slides for C++ API リファレンス
description: "2次元平面上の点の単精度浮動小数点 X および Y 座標のペアを表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 222
url: /ja/system.drawing/pointf/
---
## PointF クラス

2次元平面上の点の単精度浮動小数点 X および Y 座標のペアを表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。[System::SmartPtr](../../system/smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
class PointF
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | 指定された [SizeF](../sizef/) オブジェクトの幅と高さの値を、指定された [PointF](./) オブジェクトの X および Y 座標の値にそれぞれ加算します。 |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | 指定された [Size](../size/) オブジェクトの幅と高さの値を、指定された [PointF](./) オブジェクトの X および Y 座標の値にそれぞれ加算します。 |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが等しいかどうかを判定します。すなわち、同じ X および Y 座標のペアを表すかどうかです。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | X と Y の座標値がともに 0 であるかどうかを判定します。 |
| **float** [get_X](./get_x/)() const | 現在のオブジェクトが表す X 座標の値を返します。 |
| **float** [get_Y](./get_y/)() const | 現在のオブジェクトが表す Y 座標の値を返します。 |
| int [GetHashCode](./gethashcode/)() const | 現在のオブジェクトのハッシュコードを返します。 |
| **bool** [IsNull](./isnull/)() const | 常に false を返します。 |
| explicit  [operator bool](./operator_bool/)() | 常に true を返します。 |
|  [PointF](./pointf/)() | 新しい [PointF](./) オブジェクトを構築し、その X および Y 座標値を 0 に初期化します。 |
|  [PointF](./pointf/)(**float**, **float**) | 指定された値で新しい [PointF](./) オブジェクトを構築し、初期化します。 |
|  [PointF](./pointf/)(const [SizeF](../sizef/)\&) | 指定された [SizeF](../sizef/) オブジェクトの幅と高さの値をそれぞれ使って、新しい [PointF](./) オブジェクトの X と Y 座標値を初期化します。 |
| void [set_X](./set_x/)(**float**) | 現在のオブジェクトが表す X 座標の値を設定します。 |
| void [set_Y](./set_y/)(**float**) | 現在のオブジェクトが表す Y 座標の値を設定します。 |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | 指定された [SizeF](../sizef/) オブジェクトの幅と高さの値を、指定された [PointF](./) オブジェクトの X および Y 座標値からそれぞれ減算します。 |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | 指定された [Size](../size/) オブジェクトの幅と高さの値を、指定された [PointF](./) オブジェクトの X および Y 座標値からそれぞれ減算します。 |
| [System::String](../../system/string/) [ToString](./tostring/)() const | 現在のオブジェクトが表す X と Y 座標のペアの文字列表現を返します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static [Empty](./empty/) | [PointF](./) クラスの空のインスタンスで、X と Y 座標値は 0 です。 |

## 参照

* 名前空間 [System::Drawing](../)
* ライブラリ [Aspose.Slides](../../)