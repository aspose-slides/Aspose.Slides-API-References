---
title: SizeF
second_title: Aspose.Slides for C++ API リファレンス
description: "画像の幅と高さを表す単精度浮動小数点値のペアを表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 287
url: /ja/system.drawing/sizef/
---
## SizeF クラス

画像の幅と高さを表す単精度浮動小数点値のペアを表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。[System::SmartPtr](../../system/smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
class SizeF
```

## メソッド

| Method | Description |
| --- | --- |
| static [SizeF](./) [Add](./add/)(const [SizeF](./)\&, const [SizeF](./)\&) | 新しい [SizeF](./) オブジェクトを返します。このオブジェクトは指定された [SizeF](./) オブジェクトの合計で、幅の値は指定されたオブジェクトの幅の合計、高さの値は指定されたオブジェクトの高さの合計となります。 |
| **bool** [Equals](./equals/)(const [SizeF](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが等しいかどうかを判断します。つまり、幅と高さのペアが同じであることを示します。 |
| **float** [get_Height](./get_height/)() const | 現在のオブジェクトが表す高さの値を返します。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 幅と高さの両方の値が 0 であるかどうかを判断します。 |
| **float** [get_Width](./get_width/)() const | 現在のオブジェクトが表す幅の値を返します。 |
| **int32_t** [GetHashCode](./gethashcode/)() const | 現在のオブジェクトのハッシュコードを返します。 |
|  [operator PointF](./operator_pointf/)() const | 現在のオブジェクトを [Point](../point/) オブジェクトに変換し、その X と Y 座標を現在のオブジェクトの幅と高さの値でそれぞれ初期化します。 |
| [SizeF](./)\& [operator+=](./operator_plus_equal/)(const [SizeF](./)\&) | 指定された [SizeF](./) オブジェクトの幅と高さの値を現在の [SizeF](./) オブジェクトの幅と高さの値にそれぞれ加算します。 |
| void [set_Height](./set_height/)(**float**) | 現在のオブジェクトが表す高さの値を設定します。 |
| void [set_Width](./set_width/)(**float**) | 現在のオブジェクトが表す幅の値を設定します。 |
|  [SizeF](./sizef/)() | 幅と高さの値を 0 に初期化した新しい [SizeF](./) オブジェクトを構築します。 |
|  [SizeF](./sizef/)(const [PointF](../pointf/)\&) | 指定された点の X と Y 座標の値で幅と高さの値をそれぞれ初期化した新しい [SizeF](./) オブジェクトを構築します。 |
|  [SizeF](./sizef/)(**float**, **float**) | 指定された値で初期化された新しい [SizeF](./) オブジェクトを構築します。 |
| static [SizeF](./) [Subtract](./subtract/)(const [SizeF](./)\&, const [SizeF](./)\&) | **size2** を **size1** から減算した結果の新しい [SizeF](./) オブジェクトを返します。幅の値は **size1** の幅から **size2** の幅を減算した結果、そして高さの値は **size1** の高さから **size2** の高さを減算した結果となります。 |
| [PointF](../pointf/) [ToPointF](./topointf/)() const | 現在のオブジェクトを [Point](../point/) オブジェクトに変換し、その X と Y 座標を現在のオブジェクトの幅と高さの値でそれぞれ初期化します。 |
| [Size](../size/) [ToSize](./tosize/)() const | 現在の [SizeF](./) オブジェクトから [Size](../size/) オブジェクトを構築し、[SizeF](./) オブジェクトの幅と高さの値を次の低い整数値に切り捨てます。 |
| [System::String](../../system/string/) [ToString](./tostring/)() const | 現在のオブジェクトが表す幅と高さのペアの文字列表現を返します。 |

## フィールド

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | 幅と高さの値が 0 の [SizeF](./) クラスの空のインスタンスです。 |

## 参照

* 名前空間 [System::Drawing](../)
* ライブラリ [Aspose.Slides](../../)