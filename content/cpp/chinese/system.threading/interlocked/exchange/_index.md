---
title: Exchange()
second_title: Aspose.Slides for C++ API 参考
description: "在变量上交换值：存储新值并返回变量在存储前的值。"
type: docs
weight: 66
url: /zh/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) 方法

在变量上交换值：存储新值并返回变量在存储前的值。

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 变量类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| location1 | T\& | 要更改的变量引用。 |
| value | T | 要存储的值。 |

### 返回值

变量在更改前的值。

## Interlocked::Exchange(T\&, T) 方法

在变量上交换值：存储新值并返回变量在存储前的值。未实现。

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 变量类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| location1 | T\& | 要更改的变量引用。 |
| value | T | 要存储的值。 |

### 返回值

变量在更改前的值。

## 另请参见

* 类 [Interlocked](../)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)