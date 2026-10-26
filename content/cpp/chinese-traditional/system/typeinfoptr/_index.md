---
title: TypeInfoPtr
second_title: Aspose.Slides for C++ API 參考
description: "此為指向 TypeInfo 類別實例的指標的包裝。此類型應在堆疊上分配，並以值或參考方式傳遞給函式。切勿使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 1951
url: /zh-hant/system/typeinfoptr/
---
## TypeInfoPtr 結構

此為指向 [TypeInfo](../typeinfo/) 類別實例的指標的封裝。此類型應在堆疊上分配，並以值或參考傳遞給函式。切勿使用 [System::SmartPtr](../smartptr/) 類別來管理此類型的物件。

```cpp
class TypeInfoPtr
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [operator TypeInfo *](./operator_typeinfo__star/)() | 傳回指向所代表的 [TypeInfo](../typeinfo/) 物件的原始指標。 |
| [TypeInfoPtr](./typeinfoptr/)() | 預設建構函式。 |
| [TypeInfoPtr](./typeinfoptr/)(const std::type_info\&) | 建構函式。 |
| [TypeInfoPtr](./typeinfoptr/)(const char_t *, **uint32_t**) | 建構函式。 |
| [TypeInfoPtr](./typeinfoptr/)(const char_t *) | 建構函式。 |
| [TypeInfoPtr](./typeinfoptr/)(const [String](../string/)\&) | 建構函式。 |
| [~TypeInfoPtr](./~typeinfoptr/)() | 解構函式。 |
## 另見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)