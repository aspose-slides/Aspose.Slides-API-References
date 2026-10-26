---
title: Point
second_title: Aspose.Slides for C++ API リファレンス
description: "2 次元平面上の点の整数 X および Y 座標のペアを表します。この型はスタックに割り当て、値渡しまたは参照渡しで関数に渡すべきです。決して System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 209
url: /ja/system.drawing/point/
---
## Point クラス

2 次元平面上の点の整数 X および Y 座標のペアを表します。この型はスタックに割り当て、値渡しまたは参照渡しで関数に渡すべきです。決して [System::SmartPtr](../../system/smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
class Point
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static [Point](./) [Add](./add/)(const [Point](./)\&, const [Size](../size/)\&) | 指定された [Size](../size/) オブジェクトの幅と高さの値を、指定された [Point](./) オブジェクトの X および Y 座標値にそれぞれ加算します。 |
| static [Point](./) [Ceiling](./ceiling/)(const [PointF](../pointf/)\&) | 指定された [PointF](../pointf/) オブジェクトから [Point](./) オブジェクトを作成し、[PointF](../pointf/) オブジェクトの X および Y 座標値を次の整数に切り上げます。 |
| **bool** [Equals](./equals/)(const [Point](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが等しいかどうか、すなわち同じ X と Y 座標のペアを表しているかを判定します。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | X と Y の座標値がともに 0 であるかどうかを判定します。 |
| int [get_X](./get_x/)() const | 現在のオブジェクトが表す X 座標の値を返します。 |
| int [get_Y](./get_y/)() const | 現在のオブジェクトが表す Y 座標の値を返します。 |
| int [GetHashCode](./gethashcode/)() const | 現在のオブジェクトのハッシュコードを返します。 |
| size_t [getStdHash](./getstdhash/)() const | 現在のオブジェクトのハッシュ値を返します。 |
| **bool** [IsNull](./isnull/)() const | 常に false を返します。 |
| void [Offset](./offset/)(int, int) | 現在のオブジェクトが表す X および Y 座標値を、指定された値だけオフセットします。 |
| void [Offset](./offset/)([Point](./)) | 現在のオブジェクトが表す X および Y 座標を、指定された [Point](./) オブジェクトが表す X と Y 座標の値でそれぞれオフセットします。 |
|  [operator PointF](./operator_pointf/)() const | [PointF](../pointf/) オブジェクトのインスタンスを作成し、現在の [Point](./) オブジェクトの X および Y 座標値で初期化します。 |
|  [operator Size](./operator_size/)() const | [Size](../size/) オブジェクトのインスタンスを作成し、その幅と高さの値を現在のオブジェクトが表す X と Y 座標の値でそれぞれ初期化します。 |
|  [Point](./point/)() | 新しい [Point](./) オブジェクトを作成し、その X と Y 座標値を 0 で初期化します。 |
|  [Point](./point/)(int, int) | 新しい [Point](./) オブジェクトを作成し、指定された値で初期化します。 |
|  [Point](./point/)(const [Size](../size/)\&) | 新しい [Point](./) オブジェクトを作成し、指定された [SizeF](../sizef/) オブジェクトの幅と高さの値で X と Y 座標値をそれぞれ初期化します。 |
|  [Point](./point/)(int) | 新しい [Point](./) オブジェクトを作成し、その X 座標値を指定された 32 ビット整数の上位 16 ビットで構成した値で、Y 座標値を下位 16 ビットで構成した値で初期化します。 |
| static [Point](./) [Round](./round/)(const [PointF](../pointf/)\&) | 指定された [PointF](../pointf/) オブジェクトから [Point](./) オブジェクトを作成し、[PointF](../pointf/) オブジェクトの X および Y 座標値を最も近い整数に丸めます。 |
| void [set_X](./set_x/)(int) | 現在のオブジェクトが表す X 座標の値を設定します。 |
| void [set_Y](./set_y/)(int) | 現在のオブジェクトが表す Y 座標の値を設定します。 |
| static [Point](./) [Subtract](./subtract/)(const [Point](./)\&, const [Size](../size/)\&) | 指定された [Size](../size/) オブジェクトの幅と高さの値を、指定された [Point](./) オブジェクトの X と Y 座標値からそれぞれ減算します。 |
| [String](../../system/string/) [ToString](./tostring/)() const | 現在のオブジェクトが表す X と Y 座標のペアの文字列表現を返します。 |
| static [Point](./) [Truncate](./truncate/)(const [PointF](../pointf/)\&) | 指定された [PointF](../pointf/) オブジェクトから [Point](./) オブジェクトを作成し、[PointF](../pointf/) オブジェクトの X と Y 座標値を次の整数に切り捨てます。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static [Empty](./empty/) | X と Y の座標値が 0 の [Point](./) クラスの空のインスタンスです。 |

## 参照

* 名前空間 [System::Drawing](../)
* ライブラリ [Aspose.Slides](../../)