---
title: Is()
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 27
url: /zh-hant/system/details_systemexception/is/
---
## Details_SystemException::Is(const System::TypeInfo\&) const 方法




```cpp
bool System::Details_SystemException::Is(const System::TypeInfo &target) const override
```


### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 結構，描述要測試目前物件的型別。 |

### 回傳值

如果物件是已標記的型別或其子類別則返回 True，否則返回 false。

## 備註

檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。

## 另見

* 類別 [TypeInfo](../../typeinfo/)
* 類別 [Details_SystemException](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)