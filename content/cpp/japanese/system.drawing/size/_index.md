---
title: Size
second_title: Aspose.Slides for C++ API リファレンス
description: "幅と高さを表す整数のペアを表します。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 274
url: /ja/system.drawing/size/
---
## サイズ クラス


幅と高さを表す整数のペアを表します。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。[System::SmartPtr](../../system/smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
class Size
```

## メソッド

| Method | Description |
| --- | --- |
| static [Size](./) [Add](./add/)(const [Size](./)\&, const [Size](./)\&) | 指定された [Size](./) オブジェクトの合計となる新しい [Size](./) オブジェクトを返します。つまり、幅の値は指定されたオブジェクト群の幅の合計に等しく、高さの値は指定されたオブジェクト群の高さの合計に等しくなります。 |
| static [Size](./) [Ceiling](./ceiling/)(const [SizeF](../sizef/)\&) | 指定された [SizeF](../sizef/) オブジェクトから [Size](./) オブジェクトを作成します。この際、[SizeF](../sizef/) オブジェクトの幅と高さの値を次の整数に切り上げます。 |
| **bool** [Equals](./equals/)(const [Size](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが等しいかどうかを判定します。すなわち、同じ幅と高さの組み合わせを表すかどうかです。 |
| int [get_Height](./get_height/)() const | 現在のオブジェクトが表す高さの値を返します。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 幅と高さの両方の値が 0 であるかどうかを判定します。 |
| int [get_Width](./get_width/)() const | 現在のオブジェクトが表す幅の値を返します。 |
| **int32_t** [GetHashCode](./gethashcode/)() const | 現在のオブジェクトのハッシュコードを返します。 |
|  [operator Point](./operator_point/)() const | [Point](../point/) オブジェクトのインスタンスを作成し、その X と Y 座標を現在のオブジェクトの幅と高さの値でそれぞれ初期化します。 |
|  [operator SizeF](./operator_sizef/)() const | [SizeF](../sizef/) オブジェクトのインスタンスを作成し、現在の [Size](./) オブジェクトの幅と高さの値で初期化します。 |
| static [Size](./) [Round](./round/)(const [SizeF](../sizef/)\&) | 指定された [SizeF](../sizef/) オブジェクトから [Size](./) オブジェクトを作成します。この際、[SizeF](../sizef/) オブジェクトの幅と高さの値を最も近い整数に丸めます。 |
| void [set_Height](./set_height/)(int) | 現在のオブジェクトが表す高さの値を設定します。 |
| void [set_Width](./set_width/)(int) | 現在のオブジェクトが表す幅の値を設定します。 |
|  [Size](./size/)() | 新しい [Size](./) オブジェクトを作成し、幅と高さの値を 0 で初期化します。 |
|  [Size](./size/)(const [Point](../point/)\&) | 新しい [Size](./) オブジェクトを作成し、指定された点の X と Y 座標の値でそれぞれ幅と高さを初期化します。 |
|  [Size](./size/)(int, int) | 指定された値で新しい [Size](./) オブジェクトを作成し、初期化します。 |
| static [Size](./) [Subtract](./subtract/)(const [Size](./)\&, const [Size](./)\&) | **size1** から **size2** を減算した結果となる新しい [Size](./) オブジェクトを返します。つまり、幅の値は **size1** の幅から **size2** の幅を減算した結果になり、高さの値は **size1** の高さから **size2** の高さを減算した結果になります。 |
| [String](../../system/string/) [ToString](./tostring/)() const | 現在のオブジェクトが表す幅と高さの組み合わせの文字列表現を返します。 |
| static [Size](./) [Truncate](./truncate/)(const [SizeF](../sizef/)\&) | 指定された [SizeF](../sizef/) オブジェクトから [Size](./) オブジェクトを作成し、[SizeF](../sizef/) オブジェクトの幅と高さの値を次の低い整数に切り捨てます。 |
## フィールド

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | 幅と高さの値が 0 の空の [Size](./) クラスのインスタンスです。 |
## 参照

* 名前空間 [System::Drawing](../)
* ライブラリ [Aspose.Slides](../../)