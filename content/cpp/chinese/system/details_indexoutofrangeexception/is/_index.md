---
title: Is()
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 27
url: /zh/system/details_indexoutofrangeexception/is/
---
## 详细信息_IndexOutOfRangeException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_IndexOutOfRangeException::Is(const System::TypeInfo &target) const override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 结构，描述用于测试当前对象的类型。 |

### 返回值

如果对象是标记类型或其子类则返回 True，否则返回 false。

## 备注

检查对象是否是 targetType 描述的类型的实例。相当于 C# 的 'is' 运算符。

## 另见

* Class [TypeInfo](../../typeinfo/)
* Class [Details_IndexOutOfRangeException](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)