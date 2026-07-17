---
title: ToDecimal()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的布尔值转换为等效的十进制数。
type: docs
weight: 235
url: /zh/system/convert/todecimal/
---
## Convert::ToDecimal(bool) 方法

将指定的布尔值转换为等效的十进制数。

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) 方法

将指定的 8 位无符号整数转换为等效的十进制数。

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) 方法

将指定的 8 位有符号整数转换为等效的十进制数。

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) 方法

将指定的 16 位无符号整数转换为等效的十进制数。

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) 方法

将指定的 16 位有符号整数转换为等效的十进制数。

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) 方法

将指定的 32 位无符号整数转换为等效的十进制数。

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) 方法

将指定的 32 位有符号整数转换为等效的十进制数。

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) 方法

将指定的 64 位无符号整数转换为等效的十进制数。

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) 方法

将指定的 64 位有符号整数转换为等效的十进制数。

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) 方法

将指定的 float 数字转换为等效的十进制数。

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) 方法

将指定的 double 数字转换为等效的十进制数。

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) 方法

返回指定的十进制数。

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) 方法

不支持此转换。始终抛出 InvalidCastException。

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) 方法

不支持此转换。始终抛出 InvalidCastException。

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) 方法

将指定的空字符串转换为等效的 [Decimal](../../decimal/) 值。

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```

### 返回值

零。

## Convert::ToDecimal(const char_t *) 方法

将包含数字字符串表示的指定 c 字符串转换为等效的 [Decimal](../../decimal/) 值。

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要转换的 c 字符串 |

### 返回值

[Decimal](../../decimal/) 值等于指定 c 字符串所表示的数字

## Convert::ToDecimal(const String\&) 方法

将包含数字字符串表示的指定字符串转换为等效的 [Decimal](../../decimal/) 值。

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |

### 返回值

[Decimal](../../decimal/) 值等于指定字符串所表示的数字

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息，将包含数字字符串表示的指定字符串转换为等效的 [Decimal](../../decimal/) 值。

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字符串格式信息的对象指针 |

### 返回值

[Decimal](../../decimal/) 值等于指定字符串所表示的数字

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

使用指定的数字样式和格式信息，将包含数字字符串表示的指定字符串转换为等效的 [Decimal](../../decimal/) 值。

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 指定数字字符串表示允许样式的 NumberStyles 枚举值的按位组合 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字符串格式信息的对象指针 |

### 返回值

[Decimal](../../decimal/) 值等于指定字符串所表示的数字

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

将指定的装箱值转换为等效的 [Decimal](../../decimal/) 值。

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 装箱要转换的值的对象的共享指针 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 若装箱值的类型为 [String](../../string/) 时使用的字符串格式 |

### 返回值

与指定装箱值等效的 [Decimal](../../decimal/) 值

## 另请参见

* 枚举 [NumberStyles](../../../system.globalization/numberstyles/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [Decimal](../../decimal/)
* 类 [DateTime](../../datetime/)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [Object](../../object/)
* 结构体 [Convert](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)