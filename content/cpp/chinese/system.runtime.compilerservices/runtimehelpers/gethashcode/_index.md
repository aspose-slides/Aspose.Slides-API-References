---
title: GetHashCode()
second_title: Aspose.Slides for C++ API 参考
description: "获取任意类型的哈希码。调用 Object::GetHashCode() 来实现。"
type: docs
weight: 1
url: /zh/system.runtime.compilerservices/runtimehelpers/gethashcode/
---
## RuntimeHelpers::GetHashCode(SmartPtr\<T\> const\&) 方法

获取任意类型的哈希码。调用[Object::GetHashCode()](../../../system/object/gethashcode/)来完成此操作。

```cpp
template<typename T> static int System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode(SmartPtr<T> const &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 用于获取哈希码的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [SmartPtr](../../../system/smartptr/)\<T\> const\& | [Object](../../../system/object/) 用于获取信息。 |

### 返回值

由目标实现计算的哈希码值。

## 另见

* 类 [SmartPtr](../../../system/smartptr/)
* 类 [RuntimeHelpers](../)
* 命名空间 [System::Runtime::CompilerServices](../../)
* 库 [Aspose.Slides](../../../)