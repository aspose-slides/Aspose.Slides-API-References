---
title: RectangleF
second_title: Aspose.Slides for C++ APIリファレンス
description: "画像の左上隅の単精度浮動小数点 X および Y 座標と幅と高さで定義された矩形領域を表します。この型はスタックに割り当て、値渡しまたは参照渡しで関数に渡すべきです。System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 248
url: /ja/system.drawing/rectanglef/
---
## RectangleF クラス


画像の左上隅の単精度浮動小数点 X および Y 座標と幅と高さで定義された矩形領域を表します。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。[System::SmartPtr](../../system/smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
class RectangleF
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | 現在のオブジェクトで表される矩形内に、指定された点があるかどうかを判定します。 |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | 現在のオブジェクトで表される矩形内に、指定された点があるかどうかを判定します。 |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | 現在のオブジェクトで表される矩形内に、指定された矩形があるかどうかを判定します。 |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | 現在のオブジェクトと指定されたオブジェクトで表される矩形が同一かどうかを判定します。 |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | 指定されたエッジ位置で矩形を表す新しい [RectangleF](./) オブジェクトを構築します。 |
| **float** [get_Bottom](./get_bottom/)() const | 現在のオブジェクトで表される矩形の下端の y 座標を返します。 |
| **float** [get_Height](./get_height/)() const | 現在のオブジェクトで表される矩形の高さを返します。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 現在のオブジェクトで表される矩形の左上隅の X および Y 座標、そして幅と高さがすべて 0 であるかどうかを判定します。 |
| **float** [get_Left](./get_left/)() const | 現在のオブジェクトで表される矩形の左端の X 座標を返します。 |
| [PointF](../pointf/) [get_Location](./get_location/)() const | [PointF](../pointf/) クラスのインスタンスを返し、現在のオブジェクトで表される矩形の左上隅の位置を指定します。 |
| **float** [get_Right](./get_right/)() const | 現在のオブジェクトで表される矩形の右端の X 座標を返します。 |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | [SizeF](../sizef/) クラスのインスタンスを返し、現在のオブジェクトで表される矩形の幅と高さを指定します。 |
| **float** [get_Top](./get_top/)() const | 現在のオブジェクトで表される矩形の上端の Y 座標を返します。 |
| **float** [get_Width](./get_width/)() const | 現在のオブジェクトで表される矩形の幅を返します。 |
| **float** [get_X](./get_x/)() const | 現在のオブジェクトで表される矩形の左上隅の X 座標を返します。 |
| **float** [get_Y](./get_y/)() const | 現在のオブジェクトで表される矩形の左上隅の Y 座標を返します。 |
| int [GetHashCode](./gethashcode/)() const | 現在のオブジェクトのハッシュコードを返します。 |
| void [Inflate](./inflate/)(**float**, **float**) | 現在のオブジェクトで表される矩形の幅と高さを、矩形の幾何中心の位置を保ったまま増加させます。幅と高さは指定された量だけ両方向に増加します。 |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | 現在のオブジェクトで表される矩形の幅と高さを、矩形の幾何中心の位置を保ったまま増加させます。幅と高さは、指定されたサイズオブジェクトの幅と高さの値でそれぞれ指定された量だけ増加します。 |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | 指定されたオブジェクトで表される矩形の幅と高さを、矩形の幾何中心の位置を保ったまま増加させます。幅と高さは指定された量だけ両方向に増加します。 |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | 現在のオブジェクトで表される矩形を、指定されたオブジェクトで表される矩形との交差結果の矩形に置き換えます。 |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | 指定された矩形同士の交差結果となる矩形を返します。 |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | 現在のオブジェクトと指定されたオブジェクトで表される矩形が交差しているかどうかを判定します。 |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | 現在のオブジェクトで表される矩形の位置を、指定された量だけオフセットします。 |
| void [Offset](./offset/)(**float**, **float**) | 現在のオブジェクトで表される矩形の位置を、指定された量だけオフセットします。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 常に true を返します。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 常に false を返します。 |
|  [RectangleF](./rectanglef/)() | X と Y 座標および幅と高さが 0 に設定された矩形を表す新しい [RectangleF](./) オブジェクトのインスタンスを構築します。 |
|  [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | 指定された左上隅の座標と幅・高さで矩形を表す新しい [RectangleF](./) オブジェクトのインスタンスを構築します。 |
|  [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | [PointF](../pointf/) クラスのインスタンスで左上隅の座標を、[SizeF](../sizef/) クラスのインスタンスで幅と高さを指定した矩形を表す新しい [RectangleF](./) オブジェクトのインスタンスを構築します。 |
| explicit  [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | 指定された矩形と等価な矩形を表す新しい [RectangleF](./) オブジェクトのインスタンスを構築します。 |
| void [set_Height](./set_height/)(**float**) | 現在のオブジェクトで表される矩形の高さを設定します。 |
| void [set_Location](./set_location/)([PointF](../pointf/)) | 現在のオブジェクトで表される矩形の左上隅の位置を設定します。 |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | 現在のオブジェクトで表される矩形の幅と高さを設定します。 |
| void [set_Width](./set_width/)(**float**) | 現在のオブジェクトで表される矩形の幅を設定します。 |
| void [set_X](./set_x/)(**float**) | 現在のオブジェクトで表される矩形の左上隅の X 座標を設定します。 |
| void [set_Y](./set_y/)(**float**) | 現在のオブジェクトで表される矩形の左上隅の Y 座標を設定します。 |
| [System::String](../../system/string/) [ToString](./tostring/)() const | 現在のオブジェクトの文字列表現を返します。 |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | 指定された矩形の合成結果となる矩形を返します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static [Empty](./empty/) | 位置とサイズの値がすべて0の空の矩形です。 |

## 参照

* 名前空間 [System::Drawing](../)
* ライブラリ [Aspose.Slides](../../)