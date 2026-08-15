---
title: SizeF
second_title: Aspose.Slides for C++ API 參考文件
description: "表示一對單精度浮點值，用於表示影像的寬度與高度。此型別應在堆疊上分配，並以值或參考方式傳遞給函式。切勿使用 System::SmartPtr 類別來管理此型別的物件。"
type: docs
weight: 287
url: /zh-hant/system.drawing/sizef/
---
## SizeF 類別


表示一對單精度浮點值，用於表示影像的寬度和高度。此型別應在堆疊上分配，並以值或參考方式傳遞給函式。切勿使用 [System::SmartPtr](../../system/smartptr/) 類別來管理此型別的物件。

```cpp
class SizeF
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static [SizeF](./) [Add](./add/)(const [SizeF](./)\&, const [SizeF](./)\&) | 傳回一個新的 [SizeF](./) 物件，該物件是指定 [SizeF](./) 物件的總和，即其寬度值等於指定物件之寬度值的總和，且高度值等於指定物件之高度值的總和。 |
| **bool** [Equals](./equals/)(const [SizeF](./)\&) const | 判斷目前物件與指定物件是否相等，即它們是否代表相同的一對寬度和高度值。 |
| **float** [get_Height](./get_height/)() const | 傳回目前物件所代表的高度值。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 判斷寬度與高度值是否皆等於 0。 |
| **float** [get_Width](./get_width/)() const | 傳回目前物件所代表的寬度值。 |
| **int32_t** [GetHashCode](./gethashcode/)() const | 傳回目前物件的雜湊碼。 |
|  [operator PointF](./operator_pointf/)() const | 將目前物件轉換成 [Point](../point/) 物件的實例，並以目前物件的寬度與高度值分別初始化其 X 與 Y 座標。 |
| [SizeF](./)\& [operator+=](./operator_plus_equal/)(const [SizeF](./)\&) | 將指定的 [SizeF](./) 物件的寬度與高度值分別加到目前 [SizeF](./) 物件的寬度與高度值上。 |
| void [set_Height](./set_height/)(**float**) | 設定目前物件所代表的高度值。 |
| void [set_Width](./set_width/)(**float**) | 設定目前物件所代表的寬度值。 |
|  [SizeF](./sizef/)() | 建構一個新的 [SizeF](./) 物件，並將其寬度與高度值初始化為 0。 |
|  [SizeF](./sizef/)(const [PointF](../pointf/)\&) | 建構一個新的 [SizeF](./) 物件，並以指定點的 X 與 Y 座標值分別初始化其寬度與高度值。 |
|  [SizeF](./sizef/)(**float**, **float**) | 建構一個新的 [SizeF](./) 物件，並以指定的值進行初始化。 |
| static [SizeF](./) [Subtract](./subtract/)(const [SizeF](./)\&, const [SizeF](./)\&) | 傳回一個新的 [SizeF](./) 物件，其為 **size1** 減去 **size2** 的結果，即其寬度值為 **size1** 的寬度值減去 **size2** 的寬度值，且高度值為 **size1** 的高度值減去 **size2** 的高度值。 |
| [PointF](../pointf/) [ToPointF](./topointf/)() const | 將目前物件轉換成 [Point](../point/) 物件的實例，並以目前物件的寬度與高度值分別初始化其 X 與 Y 座標。 |
| [Size](../size/) [ToSize](./tosize/)() const | 從目前的 [SizeF](./) 物件建構一個 [Size](../size/) 物件，方法是將 [SizeF](./) 物件的寬度與高度值截斷為次低的整數值。 |
| [System::String](../../system/string/) [ToString](./tostring/)() const | 傳回目前物件所代表的寬度與高度值組合的字串表示。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static [Empty](./empty/) | [SizeF](./) 類別的空白實例，其寬度與高度值為 0。 |

## 另請參閱

* 命名空間 [System::Drawing](../)
* 函式庫 [Aspose.Slides](../../)