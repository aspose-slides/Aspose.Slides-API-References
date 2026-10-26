---
title: MulticastDelegate()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个空集合。
type: docs
weight: 1
url: /zh/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() 方法

构造一个空集合。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) 方法

相当于默认构造函数。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) 方法

对委托集合执行浅拷贝。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| o | const MulticastDelegate\& | 要从中复制委托集合的 MulticastDelegate 类实例。 |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) 方法

移动构造函数。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| o | MulticastDelegate\&& | 要从中移动委托集合的 MulticastDelegate 类实例。 |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) 方法

构造实例并将指定的委托放入委托集合。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | 要放入委托集合的委托 |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) 方法

构造实例并将指定的值放入委托集合。

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要放入新构造实例的委托集合的值的类型；该类型必须可转换为 Callback 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg | T | 要放入委托集合的值 |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) 方法

构造实例并将指定的值放入委托集合。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | 要放入委托集合的值 |

## 另见

* 类型定义 [Callback](../callback/)
* 类 [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)