---
title: MakeScopeGuard()
second_title: Aspose.Slides for C++ API 参考
description: 一个用于创建 ScopedGuard 类实例的工厂函数。
type: docs
weight: 2770
url: /zh/system/makescopeguard/
---
## System::MakeScopeGuard(F) 函数

一个工厂函数，用于创建 ScopedGuard 类的实例。

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| The | 构造的 ScopedGuard 对象将要调用的函数对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| f | F | 传递给 ScopedGuard 类构造函数的函数对象。 |

### 返回值

ScopedGuard 类的新实例

## 参见

* 结构体 [ScopeGuard](../scopeguard/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)