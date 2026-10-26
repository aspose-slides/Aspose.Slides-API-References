---
title: DbProviderFactories
second_title: Aspose.Slides C++ API 参考
description: "API 用于获取 DB provider factories。此类的对象应仅使用 System::MakeObject() 函数进行分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言故障。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 53
url: /zh/system.data.common/dbproviderfactories/
---
## DbProviderFactories 类

API 用于获取 DB provider factories。此类的对象应仅使用 [System::MakeObject()](../../system/makeobject/) 函数进行分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class DbProviderFactories
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | 按名称获取 DB provider factory。 |

## 另请参见

* 命名空间 [System::Data::Common](../)
* 库 [Aspose.Slides](../../)