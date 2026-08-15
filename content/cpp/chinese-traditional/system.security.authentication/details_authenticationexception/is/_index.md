---
title: Is()
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 27
url: /zh-hant/system.security.authentication/details_authenticationexception/is/
---
## Details_AuthenticationException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Security::Authentication::Details_AuthenticationException::Is(const System::TypeInfo &target) const override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 結構描述要測試當前物件的類型。 |

### 返回值

如果物件是標記類型或其子類別則返回 true，否則返回 false。

## 備註

檢查物件是否為 targetType 所描述的類型實例。相當於 C# 的 'is' 運算子。

## 另見

* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [Details_AuthenticationException](../)
* 命名空間 [System::Security::Authentication](../../)
* 函式庫 [Aspose.Slides](../../../)