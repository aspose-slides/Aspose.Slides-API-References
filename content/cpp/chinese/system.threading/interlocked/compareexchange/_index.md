---
title: CompareExchange()
second_title: Aspose.Slides for C++ API 参考
description: "对变量进行比较交换：检查变量是否等于特定值，仅当存储的值与预期匹配时才存储新值。"
type: docs
weight: 79
url: /zh/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T&, T, T) 方法

对变量进行比较交换：检查变量是否等于特定值，仅当存储的值与预期匹配时才存储新值。

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 变量类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| location1 | T& | 要更改的变量引用。 |
| value | T | 要存储的值。 |
| comparand | T | 在交换之前用于比较变量值的值。 |

### 返回值

操作开始时变量的值，无论是否已更改。

## Interlocked::CompareExchange(T&, T, T) 方法

对变量进行比较交换：检查变量是否等于特定值，仅当存储的值与预期匹配时才存储新值。未实现。

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 变量类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| location1 | T& | 要更改的变量引用。 |
| value | T | 要存储的值。 |
| comparand | T | 在交换之前用于比较变量值的值。 |

### 返回值

操作开始时变量的值，无论是否已更改。

## Interlocked::CompareExchange(int32_t&, int32_t, int32_t, bool&) 方法

对变量进行比较交换：检查变量是否等于特定值，仅当存储的值与预期匹配时才存储新值。

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| location1 | **int32_t**& | 要更改的变量引用。 |
| value | **int32_t** | 要存储的值。 |
| comparand | **int32_t** | 在交换之前用于比较变量值的值。 |
| succeeded | **bool**& | 交换是否发生的布尔引用，若发生则为 true，否则为 false。 |

### 返回值

操作开始时变量的值，无论是否已更改。

## 另请参见

* 类 [Interlocked](../)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)