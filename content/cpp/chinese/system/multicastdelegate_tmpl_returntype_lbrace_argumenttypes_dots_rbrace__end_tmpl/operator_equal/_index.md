---
title: operator=()
second_title: Aspose.Slides C++ API 参考
description: 将指定对象表示的委托集合分配给当前对象。结果是两个对象指向相同的委托集合。
type: docs
weight: 27
url: /zh/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_equal/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator=(const MulticastDelegate\&) 方法

将指定对象表示的委托集合分配给当前对象。结果是两个对象指向相同的委托集合。

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator=(const MulticastDelegate &o)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| o | const [MulticastDelegate](../multicastdelegate/)\& | 包含要分配给当前对象的委托集合的 MulticastDelegate 类实例。 |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator=(MulticastDelegate\&&) 方法

移动赋值运算符。

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator=(MulticastDelegate &&o) noexcept
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| o | [MulticastDelegate](../multicastdelegate/)\&& | 要从中移动委托集合的 MulticastDelegate 类实例。 |

## 另请参阅

* 方法 [MulticastDelegate](../multicastdelegate/)
* 类 [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)