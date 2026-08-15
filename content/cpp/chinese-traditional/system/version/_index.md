---
title: Version
second_title: Aspose.Slides for C++ API 參考
description: "表示版本號。此類型應分配於堆疊上，並以值或參照方式傳遞給函式。切勿使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 1470
url: /zh-hant/system/version/
---
## Version 類別

表示版本號。此類型應分配於堆疊上，並以值或參考方式傳遞給函式。切勿使用 [System::SmartPtr](../smartptr/) 類別來管理此類型的物件。

```cpp
class Version
```

## 方法

| 方法 | 描述 |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | 比較目前物件與指定物件所表示的版本。 |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | 判斷目前物件與指定物件所表示的版本號是否相等。 |
| int [get_Build](./get_build/)() const | 傳回建置號。 |
| int [get_Major](./get_major/)() const | 傳回主要版本。 |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | 傳回修訂號的高 16 位元值。 |
| int [get_Minor](./get_minor/)() const | 傳回次要版本。 |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | 傳回修訂號的低 16 位元值。 |
| int [get_Revision](./get_revision/)() const | 傳回修訂號。 |
| int [GetHashCode](./gethashcode/)() const | 傳回目前物件的雜湊碼。 |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | 將版本號的字串表示法轉換為相等的 [Version](./) 類別實例。 |
| [String](../string/) [ToString](./tostring/)() const | 傳回目前物件所表示的版本號的字串表示法。 |
| [String](../string/) [ToString](./tostring/)(int) const | 傳回目前物件所表示的版本號中指定段數的字串表示法。 |
|  [Version](./version/)(int, int, int, int) | 建構一個表示指定的主要、次要、建置和修訂值的實例。 |
|  [Version](./version/)(int, int, int) | 建構一個表示指定的主要、次要和建置值的實例。 |
|  [Version](./version/)(int, int) | 建構一個表示指定的主要值和其他值的實例。 |
|  [Version](./version/)(const [String](../string/)\&) | 建構一個表示以字串形式呈現的版本號的實例。 |
|  [Version](./version/)() | 建構一個表示版本號 0.0.-1.-1 的實例。 |

## 另見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)