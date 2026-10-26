---
title: Index
second_title: Aspose.Slides for C++ API 參考文件
description: "表示集合中的索引。索引可以來自集合的開始或結尾。此類型應在堆疊上分配，並以值或參照方式傳遞給函式。永遠不要使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 1015
url: /zh-hant/system/index/
---
## Index 類別


表示集合中的索引。索引可以來自集合的開始或結尾。此類型應在堆疊上分配，並以值或參照方式傳遞給函式。永遠不要使用 [System::SmartPtr](../smartptr/) 類別來管理此類型的物件。

```cpp
class Index : public System::Details::BoxableObjectBase
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | 判斷目前實例與指定的 [Index](./) 是否代表相同的位置。 |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | 建立相對於集合結尾的 [Index](./)。 |
| static constexpr [Index](./) [get_End](./get_end/)() | 取得代表集合結尾的 [Index](./) 物件。 |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | 取得指示索引是否來自結尾的值。 |
| static constexpr [Index](./) [get_Start](./get_start/)() | 取得代表集合開始的 [Index](./) 物件。 |
| constexpr **int32_t** [get_Value](./get_value/)() const | 取得索引值。 |
| **int32_t** [GetHashCode](./gethashcode/)() const | 回傳目前索引的雜湊碼。 |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | 將目前的 [Index](./) 轉換為相對於具有指定長度之集合開始的偏移量。 |
| constexpr [Index](./index/)() | 建構代表集合開始的實例。 |
| constexpr [Index](./index/)(**int32_t**) | 建構代表自集合開始的指定位置的實例。 |
| constexpr [Index](./index/)(**int32_t**, **bool**) | 建構代表指定索引的實例。 |
## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)