---
title: Is()
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 27
url: /zh-hant/system.io/details_invaliddataexception/is/
---
## Details_InvalidDataException::Is(const System::TypeInfo\&) const method




```cpp
bool System::IO::Details_InvalidDataException::Is(const System::TypeInfo &target) const override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) structure describing the type to test current object against. |

### 回傳值

True if object is of tagged type or its subclass, false otherwise.

## 備註


Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. 
## 參見

* Class [TypeInfo](../../../system/typeinfo/)
* Class [Details_InvalidDataException](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)