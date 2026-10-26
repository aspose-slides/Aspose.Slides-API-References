---
title: ScopeGuard
second_title: Aspose.Slides for C++ API 参考
description: 在类的实例超出作用域时，提供运行特定函数对象服务的服务类。
type: docs
weight: 1860
url: /zh/system/scopeguard/
---
## ScopeGuard 结构体

在类的实例超出作用域时，提供运行特定函数对象服务的服务类。

```cpp
template<typename F>class ScopeGuard
```

### Template parameters

| 参数 | 描述 |
| --- | --- |
| F | The type of the function object invoked by the instances of the ScopedGuard class |

## Methods

| 方法 | 描述 |
| --- | --- |
| void [Disable](./disable/)() | 禁用守护调用。 |
|   [ScopeGuard](./scopeguard/)(F) | 构造一个实例，该实例已设置为调用指定的函数对象。 |
|   [~ScopeGuard](./~scopeguard/)() | 调用传递给构造函数的函数对象。 |

## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)