---
title: Is()
second_title: Aspose.Slides for C++ API 參考手冊
description: 
type: docs
weight: 27
url: /zh-hant/system.security/details_securityexception/is/
---
## Details_SecurityException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Security::Details_SecurityException::Is(const System::TypeInfo &target) const override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 結構描述要測試目前物件的類型。 |

### 回傳值

如果物件是標記類型或其子類別則回傳 true，否則回傳 false。

## 備註

檢查物件是否代表 targetType 所描述的類型之實例。相當於 C# 的 'is' 運算子。

## 參見

* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [Details_SecurityException](../)
* 命名空間 [System::Security](../../)
* 函式庫 [Aspose.Slides](../../../)