---
title: Is()
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 27
url: /zh/system.threading/details_semaphorefullexception/is/
---
## Details_SemaphoreFullException::Is(const System::TypeInfo\&) const 方法




```cpp
bool System::Threading::Details_SemaphoreFullException::Is(const System::TypeInfo &target) const override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 结构体，描述用于测试当前对象的类型。 |

### 返回值

如果对象是标记类型或其子类则返回 True，否则返回 false。
## 备注


检查对象是否表示 targetType 描述的类型的实例。相当于 C# 的 'is' 运算符。 
## 另请参阅

* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [Details_SemaphoreFullException](../)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)