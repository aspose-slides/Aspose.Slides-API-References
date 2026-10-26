---
title: Is()
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 27
url: /zh/system/details_invalidprogramexception/is/
---
## Details_InvalidProgramException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_InvalidProgramException::Is(const System::TypeInfo &target) const override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) structure describing the type to test current object against. |

### 返回值

True if object is of tagged type or its subclass, false otherwise.
## 备注


Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. 
## 另见

* 类 [TypeInfo](../../typeinfo/)
* 类 [Details_InvalidProgramException](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)