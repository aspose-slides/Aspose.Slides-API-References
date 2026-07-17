---
title: ToChar()
second_title: Aspose.Slides for C++ API 参考
description: 不支持转换。始终抛出 InvalidCastException.
type: docs
weight: 118
url: /zh/system/convert/tochar/
---
## Convert::ToChar(bool) 方法

不支持转换。始终抛出 InvalidCastException。

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) 方法

将指定的 8 位无符号整数转换为等效的 Unicode 字符。

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) 方法

将指定的 8 位有符号整数转换为等效的 Unicode 字符。

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) 方法

将指定的 16 位无符号整数转换为等效的 Unicode 字符。

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) 方法

将指定的 16 位有符号整数转换为等效的 Unicode 字符。

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) 方法

将指定的 32 位无符号整数转换为等效的 Unicode 字符。

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) 方法

将指定的 32 位有符号整数转换为等效的 Unicode 字符。

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) 方法

将指定的 64 位无符号整数转换为等效的 Unicode 字符。

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) 方法

将指定的 64 位有符号整数转换为等效的 Unicode 字符。

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) 方法

不支持转换。始终抛出 InvalidCastException。

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) 方法

不支持转换。始终抛出 InvalidCastException。

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) 方法

不支持转换。始终抛出 InvalidCastException。

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) 方法

返回指定的 Unicode 字符。

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) 方法

不支持转换。始终抛出 InvalidCastException。

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) 方法

将指定 C 字符串的第一个且唯一的字符转换为 char_t 值。

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要转换的 C 字符串；期望该 C 字符串恰好为 1 个字符长。 |

### 返回值

如果指定的 C 字符串恰好为 1 个字符，则返回其第一个且唯一的字符；否则返回 0。

## Convert::ToChar(const String\&) 方法

将指定字符串的第一个且唯一的字符转换为 char_t 值。

```cpp
static char_t System::Convert::ToChar(const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串；期望该字符串恰好为 1 个字符长 |

### 返回值

如果指定的字符串恰好为 1 个字符，则返回其第一个且唯一的字符；否则返回 0。

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

将指定字符串的第一个且唯一的字符转换为 char_t 值。

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串；期望该字符串恰好为 1 个字符长 |

### 返回值

如果指定的字符串恰好为 1 个字符，则返回其第一个且唯一的字符；否则返回 0。

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

将指定的装箱值转换为等效的 Unicode 字符。

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 指向装箱待转换值的对象的共享指针 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 如果装箱值的类型为 [String](../../string/)，则使用的字符串格式 |

### 返回值

等效于指定装箱值的 Unicode 字符。

## 另见

* 类型别名 [SharedPtr](../../sharedptr/)
* 类 [Decimal](../../decimal/)
* 类 [DateTime](../../datetime/)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [Object](../../object/)
* 结构体 [Convert](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)