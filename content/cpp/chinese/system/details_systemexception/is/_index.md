---
title: Is()
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 27
url: /zh/system/details_systemexception/is/
---
## Details_SystemException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_SystemException::Is(const System::TypeInfo &target) const override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 结构，描述要用于测试当前对象的类型。 |

### 返回值

True if object is of tagged type or its subclass, false otherwise.

## 备注

Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. 

## 另见

* 类 [TypeInfo](../../typeinfo/)
* 类 [Details_SystemException](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)