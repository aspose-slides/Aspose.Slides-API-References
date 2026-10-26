---
title: Is()
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 27
url: /zh/system.io/details_ioexception/is/
---
## Details_IOException::Is(const System::TypeInfo\&) const 方法




```cpp
bool System::IO::Details_IOException::Is(const System::TypeInfo &target) const override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 结构，描述要与当前对象比较的类型。 |

### 返回值

如果对象是标记类型或其子类则为 True，否则为 false。

## 备注

检查对象是否为 targetType 描述的类型的实例。相当于 C# 的 'is' 运算符。

## 另见

* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [Details_IOException](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)