---
title: Is()
second_title: Aspose.Slides for C++ API 參考
description: 
type: docs
weight: 27
url: /zh-hant/system/details_invalidprogramexception/is/
---
## 詳細資訊_InvalidProgramException::Is(const System::TypeInfo\&) const 方法




```cpp
bool System::Details_InvalidProgramException::Is(const System::TypeInfo &target) const override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 描述用於測試當前物件的類型的結構。 |

### 返回值

如果物件是標記類型或其子類別則返回 true，否則返回 false。

## 備註

檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。

## 參見

* 類別 [TypeInfo](../../typeinfo/)
* 類別 [Details_InvalidProgramException](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)