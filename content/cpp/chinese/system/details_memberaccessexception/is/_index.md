---
title: Is()
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 27
url: /zh/system/details_memberaccessexception/is/
---
## Details_MemberAccessException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_MemberAccessException::Is(const System::TypeInfo &target) const override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 结构，描述用于测试当前对象的类型。 |

### 返回值

True if object is of tagged type or its subclass, false otherwise.
## 备注

检查对象是否表示 targetType 所描述的类型的实例。相当于 C# 的 'is' 运算符。 
## 另见

* Class [TypeInfo](../../typeinfo/)
* Class [Details_MemberAccessException](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)