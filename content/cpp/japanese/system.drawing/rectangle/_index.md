---
title: Rectangle
second_title: Aspose.Slides for C++ API リファレンス
description: "画像の左上隅の整数 X および Y 座標と幅と高さで定義された矩形領域を表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 235
url: /ja/system.drawing/rectangle/
---
## Rectangle クラス


画像の矩形領域を表します。この領域は左上隅の整数 X および Y 座標と幅と高さで定義されます。この型はスタック上に割り当て、値または参照で関数に渡すべきです。[System::SmartPtr](../../system/smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
class Rectangle
```

## メソッド

| Method | Description |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | [Rectangle](./) オブジェクトを、指定された [RectangleF](../rectanglef/) オブジェクトから構築します。このとき、[RectangleF](../rectanglef/) オブジェクトの位置とサイズの値を次の上位整数に丸めます。 |
| **bool** [Contains](./contains/)(int, int) const | 指定された点が現在のオブジェクトで表される矩形内にあるかどうかを判定します。 |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | 指定された点が現在のオブジェクトで表される矩形内にあるかどうかを判定します。 |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | 指定された点が現在のオブジェクトで表される矩形内にあるかどうかを判定します。 |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが表す矩形が同一かどうかを判定します。 |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | 指定されたエッジ位置で矩形を表す新しい [Rectangle](./) オブジェクトを構築します。 |
| int [get_Bottom](./get_bottom/)() const | 現在のオブジェクトで表される矩形の底辺の y 座標を返します。 |
| int [get_Height](./get_height/)() const | 現在のオブジェクトで表される矩形の高さを返します。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 現在のオブジェクトで表される矩形の左上隅の X および Y 座標、そして幅と高さがすべて 0 の値かどうかを判定します。 |
| int [get_Left](./get_left/)() const | 現在のオブジェクトで表される矩形の左端の X 座標を返します。 |
| [Point](../point/) [get_Location](./get_location/)() const | 現在のオブジェクトで表される矩形の左上隅の位置を指定する [Point](../point/) クラスのインスタンスを返します。 |
| int [get_Right](./get_right/)() const | 現在のオブジェクトで表される矩形の右端の X 座標を返します。 |
| [Size](../size/) [get_Size](./get_size/)() const | 現在のオブジェクトで表される矩形の幅と高さを指定する [Size](../size/) クラスのインスタンスを返します。 |
| int [get_Top](./get_top/)() const | 現在のオブジェクトで表される矩形の上端の Y 座標を返します。 |
| int [get_Width](./get_width/)() const | 現在のオブジェクトで表される矩形の幅を返します。 |
| int [get_X](./get_x/)() const | 現在のオブジェクトで表される矩形の左上隅の X 座標を返します。 |
| int [get_Y](./get_y/)() const | 現在のオブジェクトで表される矩形の左上隅の Y 座標を返します。 |
| int [GetHashCode](./gethashcode/)() const | 現在のオブジェクトのハッシュコードを返します。 |
| void [Inflate](./inflate/)(int, int) | 現在のオブジェクトで表される矩形の幅と高さを、矩形の幾何中心の位置を保ったまま増加させます。幅と高さは指定された量だけ両方向に増加します。 |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | 現在のオブジェクトで表される矩形の幅と高さを、矩形の幾何中心の位置を保ったまま増加させます。幅と高さは、指定されたサイズオブジェクトの幅と高さの値でそれぞれ指定された量だけ両方向に増加します。 |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | 指定されたオブジェクトで表される矩形の幅と高さを、矩形の幾何中心の位置を保ったまま増加させます。幅と高さは指定された量だけ両方向に増加します。 |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | 現在のオブジェクトで表される矩形を、指定されたオブジェクトで表される矩形との交差結果となる矩形に置き換えます。 |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | 指定された矩形の交差結果となる矩形を返します。 |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | 現在のオブジェクトと指定されたオブジェクトが表す矩形が交差するかどうかを判定します。 |
| void [Offset](./offset/)(const [Point](../point/)\&) | 現在のオブジェクトで表される矩形の位置を、指定された量だけオフセットします。 |
| void [Offset](./offset/)(int, int) | 現在のオブジェクトで表される矩形の位置を、指定された量だけオフセットします。 |
|  [operator RectangleF](./operator_rectanglef/)() const | [RectangleF](../rectanglef/) オブジェクトを返します。このオブジェクトは現在のオブジェクトで表される矩形と等価な矩形を表します。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 常に true を返します。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 常に false を返します。 |
|  [Rectangle](./rectangle/)() | [Rectangle](./) オブジェクトの新しいインスタンスを構築します。このインスタンスは X と Y の座標および幅と高さの値が 0 に設定された矩形を表します。 |
|  [Rectangle](./rectangle/)(int, int, int, int) | [Rectangle](./) オブジェクトの新しいインスタンスを構築します。このインスタンスは左上隅の座標と幅と高さを指定した矩形を表します。 |
|  [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | [Rectangle](./) オブジェクトの新しいインスタンスを構築します。このインスタンスは左上隅の座標を [Point](../point/) クラスのインスタンスで、幅と高さを [Size](../size/) クラスのインスタンスで指定した矩形を表します。 |
|  [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | [Rectangle](./) オブジェクトの新しいインスタンスを構築します。このインスタンスは指定された矩形と等価な矩形を表します。 |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | [Rectangle](./) オブジェクトを、指定された [RectangleF](../rectanglef/) オブジェクトから構築します。このとき、[RectangleF](../rectanglef/) オブジェクトの位置とサイズの値を最も近い整数に丸めます。 |
| void [set_Height](./set_height/)(int) | 現在のオブジェクトで表される矩形の高さを設定します。 |
| void [set_Location](./set_location/)([Point](../point/)) | 現在のオブジェクトで表される矩形の左上隅の位置を設定します。 |
| void [set_Size](./set_size/)([Size](../size/)) | 現在のオブジェクトで表される矩形の幅と高さを設定します。 |
| void [set_Width](./set_width/)(int) | 現在のオブジェクトで表される矩形の幅を設定します。 |
| void [set_X](./set_x/)(int) | 現在のオブジェクトで表される矩形の左上隅の X 座標を設定します。 |
| void [set_Y](./set_y/)(int) | 現在のオブジェクトで表される矩形の左上隅の Y 座標を設定します。 |
| [String](../../system/string/) [ToString](./tostring/)() const | 現在のオブジェクトの文字列表示を返します。 |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | [Rectangle](./) オブジェクトを、指定された [RectangleF](../rectanglef/) オブジェクトから構築します。このとき、[RectangleF](../rectanglef/) オブジェクトの位置とサイズの値を次の下位整数に切り捨てます。 |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | 指定された矩形の合成結果となる矩形を返します。 |

## フィールド

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | 位置とサイズの値がすべて 0 の空の矩形です。 |

## 参照

* 名前空間 [System::Drawing](../)
* ライブラリ [Aspose.Slides](../../)