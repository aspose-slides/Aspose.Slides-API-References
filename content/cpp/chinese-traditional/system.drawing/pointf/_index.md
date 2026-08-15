---
title: PointF
second_title: Aspose.Slides for C++ API 參考文件
description: "代表二維平面上點的單精度浮點 X 與 Y 座標對。此類型應在堆疊上分配，並以值或引用方式傳遞給函式。切勿使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 222
url: /zh-hant/system.drawing/pointf/
---
## PointF 類別


表示二維平面上點的單精度浮點 X 與 Y 座標對。此類型應在堆疊上分配，並以值或引用方式傳遞給函式。切勿使用 [System::SmartPtr](../../system/smartptr/) 類別來管理此類型的物件。

```cpp
class PointF
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | 將指定的 [SizeF](../sizef/) 物件的寬度和高度值相應地加到指定的 [PointF](./) 物件的 X 與 Y 座標值上。 |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | 將指定的 [Size](../size/) 物件的寬度和高度值相應地加到指定的 [PointF](./) 物件的 X 與 Y 座標值上。 |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | 判斷目前物件與指定物件是否相等，即代表相同的 X 與 Y 座標對。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 判斷 X 與 Y 兩個座標值是否皆等於 0。 |
| **float** [get_X](./get_x/)() const | 傳回目前物件所代表的 X 座標值。 |
| **float** [get_Y](./get_y/)() const | 傳回目前物件所代表的 Y 座標值。 |
| int [GetHashCode](./gethashcode/)() const | 傳回目前物件的雜湊碼。 |
| **bool** [IsNull](./isnull/)() const | 始終傳回 false。 |
| explicit  [operator bool](./operator_bool/)() | 始終傳回 true。 |
|  [PointF](./pointf/)() | 建構一個新的 [PointF](./) 物件，並以 0 初始化其 X 與 Y 座標值。 |
|  [PointF](./pointf/)(**float**, **float**) | 建構一個新的 [PointF](./) 物件，並以指定的值初始化。 |
|  [PointF](./pointf/)(const [SizeF](../sizef/)\&) | 建構一個新的 [PointF](./) 物件，並以指定的 [SizeF](../sizef/) 物件的寬度與高度值相應地初始化其 X 與 Y 座標值。 |
| void [set_X](./set_x/)(**float**) | 設定目前物件所代表的 X 座標值。 |
| void [set_Y](./set_y/)(**float**) | 設定目前物件所代表的 Y 座標值。 |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | 將指定的 [SizeF](../sizef/) 物件的寬度和高度值相應地從指定的 [PointF](./) 物件的 X 與 Y 座標值中減去。 |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | 將指定的 [Size](../size/) 物件的寬度與高度值相應地從指定的 [PointF](./) 物件的 X 與 Y 座標值中減去。 |
| [System::String](../../system/string/) [ToString](./tostring/)() const | 傳回目前物件所代表的 X 與 Y 座標值對的字串表示。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static [Empty](./empty/) | 一個空的 [PointF](./) 類別實例，其 X 與 Y 座標值為 0。 |

## 參見

* 命名空間 [System::Drawing](../)
* 函式庫 [Aspose.Slides](../../)