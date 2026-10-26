---
title: Size
second_title: Aspose.Slides for C++ API 參考文件
description: "表示一對整數值，代表圖像的寬度和高度。此類型應分配於堆疊上，並以值或參考傳遞給函式。切勿使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 274
url: /zh-hant/system.drawing/size/
---
## 尺寸類別


表示一對整數值，代表圖像的寬度和高度。此類型應分配於堆疊上，並透過值或參考傳遞給函式。切勿使用 [System::SmartPtr](../../system/smartptr/) 類別來管理此類型的物件。

```cpp
class Size
```

## 方法

| Method | Description |
| --- | --- |
| static [Size](./) [Add](./add/)(const [Size](./)\&, const [Size](./)\&) | 傳回一個新的 [Size](./) 物件，該物件是指定的 [Size](./) 物件的總和，即其寬度值等於指定物件的寬度值之總和，且高度值等於指定物件的高度值之總和。 |
| static [Size](./) [Ceiling](./ceiling/)(const [SizeF](../sizef/)\&) | 從指定的 [SizeF](../sizef/) 物件建構一個 [Size](./) 物件，方法是將 [SizeF](../sizef/) 物件的寬度與高度值向上取整至下一個整數值。 |
| **bool** [Equals](./equals/)(const [Size](./)\&) const | 判斷目前物件與指定物件是否相等，即是否代表相同的一對寬度與高度值。 |
| int [get_Height](./get_height/)() const | 傳回目前物件所表示的高度值。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 判斷寬度與高度值是否皆等於 0。 |
| int [get_Width](./get_width/)() const | 傳回目前物件所表示的寬度值。 |
| **int32_t** [GetHashCode](./gethashcode/)() const | 傳回目前物件的雜湊碼。 |
|  [operator Point](./operator_point/)() const | 建構一個 [Point](../point/) 物件的實例，並分別以目前物件的寬度與高度值初始化其 X 與 Y 座標。 |
|  [operator SizeF](./operator_sizef/)() const | 建構一個 [SizeF](../sizef/) 物件的實例，並以目前 [Size](./) 物件的寬度與高度值初始化它。 |
| static [Size](./) [Round](./round/)(const [SizeF](../sizef/)\&) | 從指定的 [SizeF](../sizef/) 物件建構一個 [Size](./) 物件，方法是將 [SizeF](../sizef/) 物件的寬度與高度值四捨五入至最接近的整數值。 |
| void [set_Height](./set_height/)(int) | 設定目前物件所表示的高度值。 |
| void [set_Width](./set_width/)(int) | 設定目前物件所表示的寬度值。 |
|  [Size](./size/)() | 建構一個新的 [Size](./) 物件，並以 0 初始化其寬度與高度值。 |
|  [Size](./size/)(const [Point](../point/)\&) | 建構一個新的 [Size](./) 物件，並分別以指定點的 X 與 Y 座標值初始化其寬度與高度值。 |
|  [Size](./size/)(int, int) | 建構一個新的 [Size](./) 物件，並以指定的值初始化。 |
| static [Size](./) [Subtract](./subtract/)(const [Size](./)\&, const [Size](./)\&) | 傳回一個新的 [Size](./) 物件，其為 **size1** 減去 **size2** 的結果，即其寬度值為 **size1** 的寬度值減去 **size2** 的寬度值，且高度值為 **size1** 的高度值減去 **size2** 的高度值。 |
| [String](../../system/string/) [ToString](./tostring/)() const | 傳回目前物件所代表的一對寬度與高度值的字串表示形式。 |
| static [Size](./) [Truncate](./truncate/)(const [SizeF](../sizef/)\&) | 從指定的 [SizeF](../sizef/) 物件建構一個 [Size](./) 物件，方法是將 [SizeF](../sizef/) 物件的寬度與高度值向下取整至下一個較低的整數值。 |

## 欄位

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | [Size](./) 類別的一個空實例，其寬度與高度值皆為 0。 |

## 另請參閱

* 命名空間 [System::Drawing](../)
* 程式庫 [Aspose.Slides](../../)