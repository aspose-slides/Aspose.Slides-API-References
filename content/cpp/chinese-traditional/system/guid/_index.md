---
title: Guid
second_title: Aspose.Slides for C++ API 參考文件
description: "代表全域唯一識別碼（Globally Unique Identifier）。此類型應分配於堆疊，並以值或參考傳遞給函式。切勿使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 885
url: /zh-hant/system/guid/
---
## Guid 類別

代表全域唯一識別碼（Globally Unique Identifier）。此類型應分配於堆疊，並以值或參考傳遞給函式。切勿使用 [System::SmartPtr](../smartptr/) 類別來管理此類型的物件。

```cpp
class Guid
```

## 方法

| 方法 | 說明 |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | 執行目前物件與指定物件所表示的 GUID 之算術比較。 |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | 判斷目前物件與指定物件所表示的 GUID 是否相等。 |
| int [GetHashCode](./gethashcode/)() const | 傳回目前物件的雜湊碼。 |
|  [Guid](./guid/)() | 建構一個代表全部為零的 GUID 之物件。 |
|  [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | 建構一個以 unsigned 8 位元整數陣列指定的 GUID 之物件。 |
|  [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | 建構一個以 unsigned 8 位元整數陣列檢視指定的 GUID 之物件。 |
|  [Guid](./guid/)(const [String](../string/)\&) | 建構一個以字串指定的 GUID 之物件。 |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | 依指定的 GUID 組件建構 [Guid](./) 類別的實例。 |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | 依指定的 GUID 組件建構 [Guid](./) 類別的實例。 |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | 依指定的無號整數與位元組建構 [Guid](./) 類別的實例。 |
|  [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | 依指定的無號整數與位元組建構 [Guid](./) 類別的實例。 |
|  [Guid](./guid/)(const [Guid](./)\&) | 建構一個與指定物件表示相同 GUID 的物件。 |
| static [Guid](./) [NewGuid](./newguid/)() | 產生新 GUID，並傳回表示該 GUID 的 [Guid](./) 物件。 |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | 判斷目前物件與指定物件所表示的 GUID 是否不相等。 |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | 將指定 [Guid](./) 物件所表示的 GUID 值指派給目前物件。 |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | 判斷目前物件與指定物件所表示的 GUID 是否相等。 |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | 將指定的 GUID 字串表示轉換為等價的 [Guid](./) 物件。 |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | 將目前物件所表示的 GUID 轉換為位元組陣列。 |
| [String](../string/) [ToString](./tostring/)() const | 將目前物件所表示的 GUID 轉換為其字串表示。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | 使用指定的字串格式將目前物件所表示的 GUID 轉換為其字串表示。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 使用指定的字串格式與文化資訊將目前物件所表示的 GUID 轉換為其字串表示。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | 嘗試將指定的字串轉換為 [Guid](./) 物件。 |
|  [~Guid](./~guid/)() | 解構子。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static [Empty](./empty/) | 代表值為 0 的 GUID。 |

## 相關參考

* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)