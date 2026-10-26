---
title: WriteLine()
second_title: Aspose.Slides for C++ API 参考
description: 将行终止字符写入流。
type: docs
weight: 118
url: /zh/system.io/textwriter/writeline/
---
## TextWriter::WriteLine() 方法

写入行终止字符到流中。

```cpp
virtual void System::IO::TextWriter::WriteLine()
```

## TextWriter::WriteLine(const SharedPtr\<Object\>\&) 方法

将指定对象的字符串表示写入流中，随后写入行终止字符。

```cpp
virtual void System::IO::TextWriter::WriteLine(const SharedPtr<Object> &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 要写入的对象 |

## TextWriter::WriteLine(bool) 方法

将指定布尔值的字符串表示写入流中，随后写入行终止字符。

```cpp
virtual void System::IO::TextWriter::WriteLine(bool value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **bool** | 要写入的值 |

## TextWriter::WriteLine(char_t) 方法

将指定字符写入流中，随后写入行终止字符。

```cpp
virtual void System::IO::TextWriter::WriteLine(char_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char_t | 要写入的值 |

## TextWriter::WriteLine(Decimal) 方法

将指定 [Decimal](../../../system/decimal/) 对象的字符串表示写入流中，随后写入行终止字符。

```cpp
virtual void System::IO::TextWriter::WriteLine(Decimal value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | 要写入的对象 |

## TextWriter::WriteLine(double) 方法

将指定双精度浮点值的字符串表示写入流中，随后写入行终止字符。

```cpp
virtual void System::IO::TextWriter::WriteLine(double value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | 要写入的值 |

## TextWriter::WriteLine(int) 方法

将指定 32 位整数值的字符串表示写入流中，随后写入行终止字符。

```cpp
virtual void System::IO::TextWriter::WriteLine(int value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 要写入的值 |

## TextWriter::WriteLine(int64_t) 方法

将指定 64 位整数值的字符串表示写入流中，随后写入行终止字符。

```cpp
virtual void System::IO::TextWriter::WriteLine(int64_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **int64_t** | 要写入的值 |

## TextWriter::WriteLine(float) 方法

将指定单精度浮点值的字符串表示写入流中，随后写入行终止字符。

```cpp
virtual void System::IO::TextWriter::WriteLine(float value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **float** | 要写入的值 |

## TextWriter::WriteLine(const String\&) 方法

将指定字符串写入流中，随后写入行终止字符。

```cpp
virtual void System::IO::TextWriter::WriteLine(const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 要写入的字符串 |

## TextWriter::WriteLine(uint32_t) 方法

将指定无符号 32 位整数值的字符串表示写入流中，随后写入行终止字符。

```cpp
virtual void System::IO::TextWriter::WriteLine(uint32_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint32_t** | 要写入的值 |

## TextWriter::WriteLine(uint64_t) 方法

将指定无符号 64 位整数值的字符串表示写入流中，随后写入行终止字符。

```cpp
virtual void System::IO::TextWriter::WriteLine(uint64_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint64_t** | 要写入的值 |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&) 方法

将指定数组中的所有字符写入流中，随后写入行终止字符。

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含待写入字符的数组 |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 方法

将指定字符数组中指定子范围的 UTF-16 字符写入流中，随后写入行终止字符。

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含待写入字符的数组 |
| index | **int32_t** | **buffer** 中子范围起始位置的 0 基索引 |
| count | **int32_t** | 要写入的子范围字符数；-1 表示子范围一直到 **buffer** 数组末尾 |

## TextWriter::WriteLine(const char_t *) 方法

将指定 C 字符串写入流中，随后写入行终止字符。

```cpp
virtual void System::IO::TextWriter::WriteLine(const char_t *value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要写入的 C 字符串 |

## TextWriter::WriteLine(const TypeInfo\&) 方法

将指定 [TypeInfo](../../../system/typeinfo/) 对象的字符串表示写入流中，随后写入行终止字符。

```cpp
virtual void System::IO::TextWriter::WriteLine(const TypeInfo &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | 要写入的对象 |

## TextWriter::WriteLine(const String\&, const TArgs\&...) 方法

将指定值按照指定格式进行格式化后写入流中，随后写入行终止字符。

```cpp
template<class...> void System::IO::TextWriter::WriteLine(const String &format, const TArgs &... args)
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

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextWriter](../)
* Class [Object](../../../system/object/)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)