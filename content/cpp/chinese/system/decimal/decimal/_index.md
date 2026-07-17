---
title: Decimal()
second_title: Aspose.Slides C++ API 参考
description: 构造一个表示 0 的实例。
type: docs
weight: 1
url: /zh/system/decimal/decimal/
---
## Decimal::Decimal() 构造函数

构造一个表示 0 的实例。

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) 构造函数

构造一个表示指定值的实例。

```cpp
System::Decimal::Decimal(std::int8_t i)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | std::int8_t | 8 位整数值，将由正在构造的 [Decimal](../) 对象表示 |

## Decimal::Decimal(std::int16_t) 构造函数

构造一个表示指定值的实例。

```cpp
System::Decimal::Decimal(std::int16_t i)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | std::int16_t | 16 位整数值，将由正在构造的 [Decimal](../) 对象表示 |

## Decimal::Decimal(std::int32_t) 构造函数

构造一个表示指定值的实例。

```cpp
System::Decimal::Decimal(std::int32_t i)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | std::int32_t | 32 位整数值，将由正在构造的 [Decimal](../) 对象表示 |

## Decimal::Decimal(std::int64_t) 构造函数

构造一个表示指定值的实例。

```cpp
System::Decimal::Decimal(std::int64_t i)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | std::int64_t | 64 位整数值，将由正在构造的 [Decimal](../) 对象表示 |

## Decimal::Decimal(std::uint8_t) 构造函数

构造一个表示指定值的实例。

```cpp
System::Decimal::Decimal(std::uint8_t i)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | std::uint8_t | 无符号 8 位整数值，将由正在构造的 [Decimal](../) 对象表示 |

## Decimal::Decimal(std::uint16_t) 构造函数

构造一个表示指定值的实例。

```cpp
System::Decimal::Decimal(std::uint16_t i)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | std::uint16_t | 无符号 16 位整数值，将由正在构造的 [Decimal](../) 对象表示 |

## Decimal::Decimal(std::uint32_t) 构造函数

构造一个表示指定值的实例。

```cpp
System::Decimal::Decimal(std::uint32_t i)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | std::uint32_t | 无符号 32 位整数值，将由正在构造的 [Decimal](../) 对象表示 |

## Decimal::Decimal(std::uint64_t) 构造函数

构造一个表示指定值的实例。

```cpp
System::Decimal::Decimal(std::uint64_t i)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | std::uint64_t | 无符号 64 位整数值，将由正在构造的 [Decimal](../) 对象表示 |

## Decimal::Decimal(float) 构造函数

构造一个表示指定值的实例。

```cpp
System::Decimal::Decimal(float f)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| f | **float** | 单精度浮点值，将由正在构造的 [Decimal](../) 对象表示 |

## Decimal::Decimal(double) 构造函数

构造一个表示指定值的实例。

```cpp
System::Decimal::Decimal(double d)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| d | **double** | 双精度浮点值，将由正在构造的 [Decimal](../) 对象表示 |

## Decimal::Decimal(const std::string\&) 构造函数

构造一个实例，其字符串表示形式由 `std::string` 类的实例指定。

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) 构造函数

从指定的组件构造一个 [Decimal](../) 对象。

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lo | **int32_t** | 值的低 32 位 |
| mid | **int32_t** | 值的中间 32 位 |
| hi | **int32_t** | 值的高 32 位 |
| isNegative | **bool** | 指定值是否为负 |
| scale | **uint8_t** | 0 到 28 范围内的 10 的幂 |

## Decimal::Decimal(const Decimal\&) 构造函数

构造一个 [Decimal](../) 类的实例，其表示的数字与指定的 [Decimal](../) 对象相同。

```cpp
System::Decimal::Decimal(const Decimal &d)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| d | const [Decimal](../)\& | 从该 [Decimal](../) 对象复制值的来源 |

## Decimal::Decimal(const ArrayPtr\<int32_t\>\&) 构造函数

从包含二进制表示的整数数组构造一个 [Decimal](../) 类的实例。

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)\<**int32_t**\>\& | 包含二进制表示的整数数组。 |

## Decimal::Decimal(std::nullptr_t) 构造函数

始终抛出 ArgumentNullException。

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type\&) 构造函数

构造一个 [Decimal](../) 类的实例，表示指定的值。

```cpp
System::Decimal::Decimal(const number_type &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [number_type](../number_type/)\& | 生成正在构造的对象的值的常量引用 |

## 另见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类型定义 [number_type](../number_type/)
* 类 [Decimal](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)