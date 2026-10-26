---
title: RectangleF
second_title: Aspose.Slides C++ API 參考
description: "表示圖像中的矩形區域，此區域以單精度浮點的 X、Y 座標（左上角）以及寬度和高度定義。此類型應在堆疊上配置，並以值或參考方式傳遞至函式。切勿使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 248
url: /zh-hant/system.drawing/rectanglef/
---
## RectangleF 類別


代表影像中的矩形區域，此區域以單精度浮點的 X、Y 座標（左上角）以及寬度與高度定義。此類型應在堆疊上配置，並以值或參考方式傳遞至函式。切勿使用 [System::SmartPtr](../../system/smartptr/) 類別來管理此類型的物件。

```cpp
class RectangleF
```

## 方法

| Method | Description |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | 判斷指定的點是否位於目前物件所代表的矩形內。 |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | 判斷指定的點是否位於目前物件所代表的矩形內。 |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | 判斷指定的矩形是否位於目前物件所代表的矩形內。 |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | 判斷目前與指定物件所代表的矩形是否相同。 |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | 建立一個新的 [RectangleF](./) 物件，代表具有指定邊界位置的矩形。 |
| **float** [get_Bottom](./get_bottom/)() const | 傳回目前物件所代表的矩形底部邊緣的 y 座標。 |
| **float** [get_Height](./get_height/)() const | 傳回目前物件所代表的矩形的高度。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 判斷目前物件所代表的矩形左上角的 X、Y 座標以及其寬度和高度是否全部為 0。 |
| **float** [get_Left](./get_left/)() const | 傳回目前物件所代表的矩形左邊緣的 X 座標。 |
| [PointF](../pointf/) [get_Location](./get_location/)() const | 傳回一個 [PointF](../pointf/) 類別的實例，指定目前物件所代表的矩形左上角的位置。 |
| **float** [get_Right](./get_right/)() const | 傳回目前物件所代表的矩形右邊緣的 X 座標。 |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | 傳回一個 [SizeF](../sizef/) 類別的實例，指定目前物件所代表的矩形的寬度與高度。 |
| **float** [get_Top](./get_top/)() const | 傳回目前物件所代表的矩形上邊緣的 Y 座標。 |
| **float** [get_Width](./get_width/)() const | 傳回目前物件所代表的矩形的寬度。 |
| **float** [get_X](./get_x/)() const | 傳回目前物件所代表的矩形左上角的 X 座標。 |
| **float** [get_Y](./get_y/)() const | 傳回目前物件所代表的矩形左上角的 Y 座標。 |
| int [GetHashCode](./gethashcode/)() const | 傳回目前物件的雜湊碼。 |
| void [Inflate](./inflate/)(**float**, **float**) | 在保持矩形幾何中心位置不變的情況下，增加目前物件所代表的矩形的寬度與高度。寬度與高度會在兩個方向上依指定量增加。 |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | 在保持矩形幾何中心位置不變的情況下，增加目前物件所代表的矩形的寬度與高度。寬度與高度會在兩個方向上根據指定尺寸物件之寬度與高度值的相應量增加。 |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | 在保持矩形幾何中心位置不變的情況下，增加指定物件所代表的矩形的寬度與高度。寬度與高度會在兩個方向上依指定量增加。 |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | 將目前物件所代表的矩形取代為其與指定物件所代表的矩形相交之後的結果矩形。 |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | 傳回兩個指定矩形相交的結果矩形。 |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | 判斷目前與指定物件所代表的矩形是否相交。 |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | 依指定量偏移目前物件所代表的矩形的位置。 |
| void [Offset](./offset/)(**float**, **float**) | 依指定量偏移目前物件所代表的矩形的位置。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 始終傳回 true。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 始終傳回 false。 |
|  [RectangleF](./rectanglef/)() | 建立一個新的 [RectangleF](./) 物件實例，其 X、Y 座標以及寬度與高度皆設定為 0。 |
|  [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | 建立一個新的 [RectangleF](./) 物件實例，代表具有指定左上角座標、寬度與高度的矩形。 |
|  [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | 建立一個新的 [RectangleF](./) 物件實例，其左上角座標以 [PointF](../pointf/) 類別的實例指定，寬度與高度則以 [SizeF](../sizef/) 類別的實例指定。 |
| explicit  [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | 建立一個新的 [RectangleF](./) 物件實例，代表等同於指定矩形的矩形。 |
| void [set_Height](./set_height/)(**float**) | 設定目前物件所代表的矩形的高度。 |
| void [set_Location](./set_location/)([PointF](../pointf/)) | 設定目前物件所代表的矩形左上角的位置。 |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | 設定目前物件所代表的矩形的寬度與高度。 |
| void [set_Width](./set_width/)(**float**) | 設定目前物件所代表的矩形的寬度。 |
| void [set_X](./set_x/)(**float**) | 設定目前物件所代表的矩形左上角的 X 座標。 |
| void [set_Y](./set_y/)(**float**) | 設定目前物件所代表的矩形左上角的 Y 座標。 |
| [System::String](../../system/string/) [ToString](./tostring/)() const | 傳回目前物件的字串表示。 |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | 傳回兩個指定矩形合併（聯集）的結果矩形。 |

## 欄位

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | 空的矩形，即位置與大小值皆為零的矩形。 |

## 另請參閱

* 命名空間 [System::Drawing](../)
* 函式庫 [Aspose.Slides](../../)