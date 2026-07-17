---
title: Write()
second_title: Aspose.Slides C++ API 参考
description: 将指定的无符号 8 位整数值写入输出流。
type: docs
weight: 92
url: /zh/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) 方法

将指定的无符号 8 位整数值写入输出流。

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint8_t** | 要写入的值 |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) 方法

将指定字节数组中指定的字节子范围写入输出流。

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要写入的字节的数组 |
| index | int | 在 **buffer** 中子范围写入开始处的基于 0 的索引 |
| count | int | 要写入的子范围中元素的数量；-1 表示子范围在 **buffer** 数组结束处结束 |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) 方法

将指定字符数组中指定的 UTF-16 字符子范围写入输出流。

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含要写入的字符的数组 |
| index | int | 在 **buffer** 中子范围写入开始处的基于 0 的索引 |
| count | int | 要写入的子范围中字符的数量；-1 表示子范围在 **buffer** 数组结束处结束 |

## BinaryWriter::Write(bool) 方法

如果 **value** 为 true，则写入值为 0 的单字节；如果 **value** 为 false，则写入值为 1 的单字节到输出流。

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **bool** | 指定写入到输出流的字节值的布尔值 |

## BinaryWriter::Write(char16_t) 方法

将指定的 16 位宽字符值写入输出流。

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char16_t | 要写入的值 |

## BinaryWriter::Write(int16_t) 方法

将指定的 16 位整数值写入输出流。

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **int16_t** | 要写入的值 |

## BinaryWriter::Write(int) 方法

将指定的 32 位整数值写入输出流。

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 要写入的值 |

## BinaryWriter::Write(int64_t) 方法

将指定的 64 位整数值写入输出流。

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **int64_t** | 要写入的值 |

## BinaryWriter::Write(uint16_t) 方法

将指定的无符号 16 位整数值写入输出流。

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint16_t** | 要写入的值 |

## BinaryWriter::Write(uint32_t) 方法

将指定的无符号 32 位整数值写入输出流。

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint32_t** | 要写入的值 |

## BinaryWriter::Write(uint64_t) 方法

将指定的无符号 64 位整数值写入输出流。

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint64_t** | 要写入的值 |

## BinaryWriter::Write(float) 方法

将指定的单精度浮点值写入输出流。

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **float** | 要写入的值 |

## BinaryWriter::Write(double) 方法

将指定的双精度浮点值写入输出流。

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | 要写入的值 |

## BinaryWriter::Write(const Decimal\&) 方法

将指定 [Decimal](../../../system/decimal/) 值的字节表示写入输出流。

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | 要写入的值 |

## BinaryWriter::Write(const String\&) 方法

将当前编码的长度前缀字符串写入输出流。

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 要写入的字符串 |

## BinaryWriter::Write(const char_t *) 方法

将当前编码的长度前缀字符串写入输出流。

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要写入的 C 字符串 |

## 另请参阅

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BinaryWriter](../)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)