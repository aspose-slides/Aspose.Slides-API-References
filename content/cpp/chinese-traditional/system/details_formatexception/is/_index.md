---
title: Is()
second_title: Aspose.Slides for C++ API 參考
description: 
type: docs
weight: 27
url: /zh-hant/system/details_formatexception/is/
---
## 詳細_FormatException::Is(const System::TypeInfo\&) const 方法

```cpp
bool System::Details_FormatException::Is(const System::TypeInfo &target) const override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 結構描述要測試當前物件的類型。 |

### 回傳值

如果物件是已標記的類型或其子類別則返回 true，否則返回 false。

## 備註

檢查物件是否為 targetType 描述的類型之實例。相當於 C# 的 'is' 運算子。

## 另請參閱

* 類別 [TypeInfo](../../typeinfo/)
* 類別 [Details_FormatException](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)