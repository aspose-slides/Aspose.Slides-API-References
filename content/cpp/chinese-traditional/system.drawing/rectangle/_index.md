---
title: Rectangle
second_title: Aspose.Slides for C++ API 參考
description: "表示圖像中以整數 X 與 Y 座標定義左上角以及寬度與高度的矩形區域。此類型應在堆疊上分配，並以值或參考方式傳遞給函式。切勿使用 System::SmartPtr 類別管理此類型的物件。"
type: docs
weight: 235
url: /zh-hant/system.drawing/rectangle/
---
## Rectangle 類別

表示影像中以整數 X 與 Y 座標定義左上角以及寬度與高度的矩形區域。此類型應在堆疊上分配，並以值或參考方式傳遞給函式。切勿使用 [System::SmartPtr](../../system/smartptr/) 類別來管理此類型的物件。

```cpp
class Rectangle
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | 從指定的 [RectangleF](../rectanglef/) 物件建構一個 [Rectangle](./) 物件，方法是將 [RectangleF](../rectanglef/) 物件的位置和大小值四捨五入至較高的整數值。 |
| **bool** [Contains](./contains/)(int, int) const | 判斷指定的點是否位於目前物件所代表的矩形內。 |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | 判斷指定的點是否位於目前物件所代表的矩形內。 |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | 判斷指定的矩形是否位於目前物件所代表的矩形內。 |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | 判斷目前與指定物件所代表的矩形是否相同。 |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | 建立一個新的 [Rectangle](./) 物件，其矩形由指定的邊界位置表示。 |
| int [get_Bottom](./get_bottom/)() const | 傳回目前物件所代表的矩形底部邊緣的 y 座標。 |
| int [get_Height](./get_height/)() const | 傳回目前物件所代表的矩形的高度。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 判斷目前物件所代表的矩形之左上角 X 與 Y 座標以及寬度與高度是否皆為 0。 |
| int [get_Left](./get_left/)() const | 傳回目前物件所代表的矩形左邊緣的 X 座標。 |
| [Point](../point/) [get_Location](./get_location/)() const | 傳回一個 [Point](../point/) 類別的實例，該實例指定目前物件所代表的矩形左上角的位置。 |
| int [get_Right](./get_right/)() const | 傳回目前物件所代表的矩形右邊緣的 X 座標。 |
| [Size](../size/) [get_Size](./get_size/)() const | 傳回一個 [Size](../size/) 類別的實例，該實例指定目前物件所代表的矩形的寬度與高度。 |
| int [get_Top](./get_top/)() const | 傳回目前物件所代表的矩形頂部邊緣的 Y 座標。 |
| int [get_Width](./get_width/)() const | 傳回目前物件所代表的矩形的寬度。 |
| int [get_X](./get_x/)() const | 傳回目前物件所代表的矩形左上角的 X 座標。 |
| int [get_Y](./get_y/)() const | 傳回目前物件所代表的矩形左上角的 Y 座標。 |
| int [GetHashCode](./gethashcode/)() const | 傳回目前物件的雜湊碼。 |
| void [Inflate](./inflate/)(int, int) | 在保持矩形幾何中心位置不變的情況下，將目前物件所代表的矩形的寬度與高度向兩側擴增指定的數量。 |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | 在保持矩形幾何中心位置不變的情況下，將目前物件所代表的矩形的寬度與高度向兩側擴增，擴增量由指定的大小物件的寬度與高度值決定。 |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | 在保持矩形幾何中心位置不變的情況下，將指定物件所代表的矩形的寬度與高度向兩側擴增指定的數量。 |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | 以目前物件與指定物件的交集矩形取代目前物件所代表的矩形。 |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | 傳回兩個指定矩形交集的結果矩形。 |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | 判斷目前與指定物件所代表的矩形是否相交。 |
| void [Offset](./offset/)(const [Point](../point/)\&) | 依指定的數量偏移目前物件所代表的矩形的位置。 |
| void [Offset](./offset/)(int, int) | 依指定的數量偏移目前物件所代表的矩形的位置。 |
| [operator RectangleF](./operator_rectanglef/)() const | 傳回一個 [RectangleF](../rectanglef/) 物件，該物件代表與目前物件所代表的矩形等價的矩形。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 始終傳回 true。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 始終傳回 false。 |
| [Rectangle](./rectangle/)() | 建立一個新的 [Rectangle](./) 物件實例，其矩形的 X、Y 座標以及寬度與高度皆設定為 0。 |
| [Rectangle](./rectangle/)(int, int, int, int) | 建立一個新的 [Rectangle](./) 物件實例，其矩形由指定的左上角座標以及寬度與高度構成。 |
| [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | 建立一個新的 [Rectangle](./) 物件實例，其矩形的左上角座標以 [Point](../point/) 類別的實例指定，寬度與高度則以 [Size](../size/) 類別的實例指定。 |
| [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | 建立一個新的 [Rectangle](./) 物件實例，該矩形等價於指定的矩形。 |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | 從指定的 [RectangleF](../rectanglef/) 物件建構 [Rectangle](./) 物件，方法是將 [RectangleF](../rectanglef/) 物件的位置與大小值四捨五入至最近的整數值。 |
| void [set_Height](./set_height/)(int) | 設定目前物件所代表的矩形的高度。 |
| void [set_Location](./set_location/)([Point](../point/)) | 設定目前物件所代表的矩形的左上角位置。 |
| void [set_Size](./set_size/)([Size](../size/)) | 設定目前物件所代表的矩形的寬度與高度。 |
| void [set_Width](./set_width/)(int) | 設定目前物件所代表的矩形的寬度。 |
| void [set_X](./set_x/)(int) | 設定目前物件所代表的矩形的左上角 X 座標。 |
| void [set_Y](./set_y/)(int) | 設定目前物件所代表的矩形的左上角 Y 座標。 |
| [String](../../system/string/) [ToString](./tostring/)() const | 傳回目前物件的字串表示。 |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | 從指定的 [RectangleF](../rectanglef/) 物件建構 [Rectangle](./) 物件，方法是將 [RectangleF](../rectanglef/) 物件的位置與大小值截斷為較低的整數值。 |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | 傳回兩個指定矩形合併（並集）的結果矩形。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static [Empty](./empty/) | 一個空的矩形，即位置與大小值皆為零的矩形。 |

## 另請參閱

* 命名空間 [System::Drawing](../)
* 函式庫 [Aspose.Slides](../../)