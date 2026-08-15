---
title: Is()
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 27
url: /zh-hant/system/details_platformnotsupportedexception/is/
---
## Details_PlatformNotSupportedException::Is(const System::TypeInfo\&) const 方法

```cpp
bool System::Details_PlatformNotSupportedException::Is(const System::TypeInfo &target) const override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) structure describing the type to test current object against. |

### 傳回值

True if object is of tagged type or its subclass, false otherwise.

## 備註

Check if object represents an instance of type described by targetType. Analog of C# 'is' operator.

## 參見

* 類別 [TypeInfo](../../typeinfo/)
* 類別 [Details_PlatformNotSupportedException](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)