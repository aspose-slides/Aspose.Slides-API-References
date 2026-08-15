---
title: Point
second_title: Aspose.Slides for C++ API 參考
description: "表示二維平面上點的整數 X 與 Y 座標對。此類型應在堆疊上分配，並以值或參考方式傳遞給函式。切勿使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 209
url: /zh-hant/system.drawing/point/
---
## Point 類別


表示二維平面上一個點的整數 X 與 Y 座標對。此類型應該在堆疊上分配，並以值或引用方式傳遞給函式。切勿使用 [System::SmartPtr](../../system/smartptr/) 類別來管理此類型的物件。

```cpp
class Point
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [Point](./) [Add](./add/)(const [Point](./)\&, const [Size](../size/)\&) | 將指定的 [Size](../size/) 物件的寬度與高度值分別加到指定的 [Point](./) 物件的 X 與 Y 座標值上。 |
| static [Point](./) [Ceiling](./ceiling/)(const [PointF](../pointf/)\&) | 從指定的 [PointF](../pointf/) 物件建立 [Point](./) 物件，方法是將 [PointF](../pointf/) 物件的 X 與 Y 座標值向上捨入至下一個較大的整數。 |
| **bool** [Equals](./equals/)(const [Point](./)\&) const | 判斷目前物件與指定物件是否相等，即它們是否代表相同的 X 與 Y 座標值對。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 判斷 X 與 Y 座標值是否皆等於 0。 |
| int [get_X](./get_x/)() const | 傳回目前物件所代表的 X 座標值。 |
| int [get_Y](./get_y/)() const | 傳回目前物件所代表的 Y 座標值。 |
| int [GetHashCode](./gethashcode/)() const | 傳回目前物件的雜湊碼。 |
| size_t [getStdHash](./getstdhash/)() const | 傳回目前物件的雜湊值。 |
| **bool** [IsNull](./isnull/)() const | 永遠傳回 false。 |
| void [Offset](./offset/)(int, int) | 將目前物件所代表的 X 與 Y 座標值以指定的數值做偏移。 |
| void [Offset](./offset/)([Point](./)) | 將目前物件所代表的 X 與 Y 座標，以指定的 [Point](./) 物件所代表的 X 與 Y 座標值分別做偏移。 |
|  [operator PointF](./operator_pointf/)() const | 建立一個 [PointF](../pointf/) 物件的實例，並以目前 [Point](./) 物件的 X 與 Y 座標值進行初始化。 |
|  [operator Size](./operator_size/)() const | 建立一個 [Size](../size/) 物件的實例，並分別以目前物件所代表的 X 與 Y 座標值來初始化其寬度與高度。 |
|  [Point](./point/)() | 建立一個新的 [Point](./) 物件，並將其 X 與 Y 座標值初始化為 0。 |
|  [Point](./point/)(int, int) | 建立一個新的 [Point](./) 物件，並以指定的值進行初始化。 |
|  [Point](./point/)(const [Size](../size/)\&) | 建立一個新的 [Point](./) 物件，並分別以指定的 [SizeF](../sizef/) 物件的寬度與高度值來初始化其 X 與 Y 座標值。 |
|  [Point](./point/)(int) | 建立一個新的 [Point](./) 物件，並以指定 32 位元整數的高 16 位元組成 X 座標值，低 16 位元組成 Y 座標值進行初始化。 |
| static [Point](./) [Round](./round/)(const [PointF](../pointf/)\&) | 從指定的 [PointF](../pointf/) 物件建立 [Point](./) 物件，方法是將 [PointF](../pointf/) 物件的 X 與 Y 座標值四捨五入至最接近的整數。 |
| void [set_X](./set_x/)(int) | 設定目前物件所代表的 X 座標值。 |
| void [set_Y](./set_y/)(int) | 設定目前物件所代表的 Y 座標值。 |
| static [Point](./) [Subtract](./subtract/)(const [Point](./)\&, const [Size](../size/)\&) | 將指定的 [Size](../size/) 物件的寬度與高度值分別從指定的 [Point](./) 物件的 X 與 Y 座標值中減去。 |
| [String](../../system/string/) [ToString](./tostring/)() const | 傳回目前物件所代表的 X 與 Y 座標值對的字串表示。 |
| static [Point](./) [Truncate](./truncate/)(const [PointF](../pointf/)\&) | 從指定的 [PointF](../pointf/) 物件建立 [Point](./) 物件，方法是將 [PointF](../pointf/) 物件的 X 與 Y 座標值截斷至下一個較低的整數。 |

## 欄位

| 欄位 | 描述 |
| --- | --- |
| static [Empty](./empty/) | 一個 [Point](./) 類別的空實例，其 X 與 Y 座標值為 0。 |

## 另請參閱

* 命名空間 [System::Drawing](../)
* 函式庫 [Aspose.Slides](../../)