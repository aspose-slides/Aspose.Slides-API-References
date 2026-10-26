---
title: Func()
second_title: Aspose.Slides for C++ API 参考
description: 默认构造函数，创建 null-Func。
type: docs
weight: 1
url: /zh/system/func/func/
---
## Func::Func() 构造函数

默认构造函数，创建 null-Func。

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) 构造函数

构造函数用于构造 [Func](../) 对象并将值（实际回调或 nullptr）分配给它。

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 参数类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg | T\&& | 参数。 |

## Func::Func(const Func\&) 构造函数

拷贝构造函数。

```cpp
System::Func<Args>::Func(const Func &func)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| func | const [Func](../)\& | 用于从 [Object](../../object/) 复制数据。 |

## Func::Func(Func\&&) 构造函数

移动构造函数。

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| func | [Func](../)\&& | 用于从 [Object](../../object/) 移动数据。 |

## 另见

* 类 [Func](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)