---
title: Is()
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 27
url: /zh-hant/system.io/details_ioexception/is/
---
## Details_IOException::Is(const System::TypeInfo\&) const method




```cpp
bool System::IO::Details_IOException::Is(const System::TypeInfo &target) const override
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 結構，描述要用於測試當前物件的類型。 |

### 傳回值

若物件是已標記的類型或其子類別則回傳 True，否則回傳 false。

## 備註

檢查物件是否為 targetType 所描述的類型之實例。相當於 C# 的 'is' 運算子。

## 相關參考

* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [Details_IOException](../)
* 名稱空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)