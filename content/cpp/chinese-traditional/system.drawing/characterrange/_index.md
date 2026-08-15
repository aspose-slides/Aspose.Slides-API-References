---
title: CharacterRange
second_title: Aspose.Slides for C++ API 參考說明
description: "表示字串中字元位置的範圍。此類型應在堆疊上分配，並以值或參考方式傳遞給函式。切勿使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 40
url: /zh-hant/system.drawing/characterrange/
---
## CharacterRange 類別


表示字串中字元位置的範圍。此類型應在堆疊上配置，並以值或參考方式傳遞給函式。切勿使用 [System::SmartPtr](../../system/smartptr/) 類別來管理此類型的物件。

```cpp
class CharacterRange
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | 建構一個 [CharacterRange](./) 類別的新實例，以表示指定的範圍。 |
|  [CharacterRange](./characterrange/)() | 建構一個 [CharacterRange](./) 類別的新實例，以表示空的範圍。 |
| **int32_t** [get_First](./get_first/)() const | 傳回目前物件所代表之範圍中第一個字元的位置。 |
| **int32_t** [get_Length](./get_length/)() const | 傳回目前物件所代表之範圍中的字元數量。 |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | 判斷目前物件與指定物件是否代表不同的範圍。 |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | 判斷目前物件與指定物件是否代表相同的範圍。 |
| void [set_First](./set_first/)(**int32_t**) | 設定目前物件所代表之範圍中第一個字元的位置。 |
| void [set_Length](./set_length/)(**int32_t**) | 傳回目前物件所代表之範圍中的字元數量。 |
## 另請參閱

* 命名空間 [System::Drawing](../)
* 程式庫 [Aspose.Slides](../../)