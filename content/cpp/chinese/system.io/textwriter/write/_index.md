---
title: Write()
second_title: Aspose.Slides for C++ API 参考
description: 将指定对象的字符串表示写入流中。
type: docs
weight: 105
url: /zh/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) 方法

将指定对象的字符串表示写入流中。

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 要写入的对象 |

## TextWriter::Write(bool) 方法

将指定布尔值的字符串表示写入流中。

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **bool** | 要写入的值 |

## TextWriter::Write(char_t) 方法

将指定字符写入流中。

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char_t | 要写入的值 |

## TextWriter::Write(Decimal) 方法

将指定 [Decimal](../../../system/decimal/) 对象的字符串表示写入流中。

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | 要写入的对象 |

## TextWriter::Write(double) 方法

将指定的双精度浮点值的字符串表示写入流中。

```cpp
virtual void System::IO::TextWriter::Write(double value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | 要写入的值 |

## TextWriter::Write(int) 方法

将指定的 32 位整数值的字符串表示写入流中。

```cpp
virtual void System::IO::TextWriter::Write(int value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 要写入的值 |

## TextWriter::Write(int64_t) 方法

将指定的 64 位整数值的字符串表示写入流中。

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **int64_t** | 要写入的值 |

## TextWriter::Write(float) 方法

将指定的单精度浮点值的字符串表示写入流中。

```cpp
virtual void System::IO::TextWriter::Write(float value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **float** | 要写入的值 |

## TextWriter::Write(const String\&) 方法

将指定字符串写入流中。

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 要写入的字符串 |

## TextWriter::Write(uint32_t) 方法

将指定的无符号 32 位整数值的字符串表示写入流中。

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint32_t** | 要写入的值 |

## TextWriter::Write(uint64_t) 方法

将指定的无符号 64 位整数值的字符串表示写入流中。

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint64_t** | 要写入的值 |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) 方法

将指定数组中的所有字符写入流中。

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 要写入的字符数组 |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 方法

将指定字符数组中指定的 UTF-16 子范围字符写入流中。

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 要写入的字符数组 |
| index | **int32_t** | 在 **buffer** 中子范围写入开始位置的基于 0 的索引 |
| count | **int32_t** | 要写入的子范围字符数；-1 表示子范围在 **buffer** 数组结束处结束 |

## TextWriter::Write(const char_t *) 方法

将指定的 C 字符串写入流中。

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要写入的 C 字符串 |

## TextWriter::Write(const TypeInfo\&) 方法

将指定 [TypeInfo](../../../system/typeinfo/) 对象的字符串表示写入流中。

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | 要写入的对象 |

## TextWriter::Write(const String\&, const TArgs\&...) 方法

根据指定的格式将指定的值写入流中。

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TArgs | 要写入的值的类型列表 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | 字符串格式 |
| args | const TArgs\&... | 要写入的值 |

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [Object](../../../system/object/)
* 类 [TextWriter](../)
* 类 [Decimal](../../../system/decimal/)
* 类 [String](../../../system/string/)
* 类 [TypeInfo](../../../system/typeinfo/)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)