---
title: Is()
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 27
url: /zh-hant/system.threading/details_threadabortexception/is/
---
## Details_ThreadAbortException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Threading::Details_ThreadAbortException::Is(const System::TypeInfo &target) const override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 結構，用於描述要測試目前物件的型別。 |

### 返回值

若物件屬於標記型別或其子類別則為 true，否則為 false。

## 備註

檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。

## 另見

* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [Details_ThreadAbortException](../)
* 命名空間 [System::Threading](../../)
* 程式庫 [Aspose.Slides](../../../)