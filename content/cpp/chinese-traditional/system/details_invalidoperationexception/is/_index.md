---
title: Is()
second_title: Aspose.Slides for C++ API 參考
description: 
type: docs
weight: 27
url: /zh-hant/system/details_invalidoperationexception/is/
---
## Details_InvalidOperationException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_InvalidOperationException::Is(const System::TypeInfo &target) const override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 結構描述要測試當前物件的類型。 |

### 傳回值

如果物件是標記類型或其子類別則回傳 true，否則回傳 false。

## 備註

Check if object represents an instance of type described by targetType. Analog of C# 'is' operator.

## 另見

* 類別 [TypeInfo](../../typeinfo/)
* 類別 [Details_InvalidOperationException](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)