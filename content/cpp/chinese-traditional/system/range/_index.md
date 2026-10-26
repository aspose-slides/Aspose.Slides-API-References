---
title: Range
second_title: Aspose.Slides C++ 版 API 參考
description: "代表具有起始和結束索引的範圍。此類型應在堆疊上配置，並以值或參考傳遞給函式。永遠不要使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 1197
url: /zh-hant/system/range/
---
## Range 類別

代表具有起始和結束索引的範圍。此類型應在堆疊上配置，並以值或參考傳遞給函式。永遠不要使用 [System::SmartPtr](../smartptr/) 類別來管理此類型的物件。

```cpp
class Range : public System::Details::BoxableObjectBase
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | 建立一個範圍，起始於集合的開始，並在指定的結束索引結束。 |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | 判斷目前的範圍是否等於指定的範圍。 |
| static constexpr [Range](./) [get_All](./get_all/)() | 傳回一個 [Range](./)，代表整個集合。 |
| const [Index](../index/)\& [get_End](./get_end/)() const | 取得 End 索引。 |
| const [Index](../index/)\& [get_Start](./get_start/)() const | 取得 Start 索引。 |
| **int32_t** [GetHashCode](./gethashcode/)() const | 傳回目前範圍的雜湊碼。 |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | 計算指定集合長度的零基起始偏移量與長度。 |
| constexpr [Range](./range/)() | 建構一個空的範圍。 |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | 從指定的起始與結束索引建構一個 [Range](./)。 |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | 建立一個範圍，起始於指定的起始索引，並延伸至集合的結束。 |

## 參見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)