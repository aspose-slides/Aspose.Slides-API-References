---
title: ToDouble()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的布尔值转换为等价的双精度浮点数。
type: docs
weight: 222
url: /zh/system/convert/todouble/
---
## Convert::ToDouble(bool) 方法

将指定的 boolean 值转换为等价的 double 精度浮点数。

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) 方法

将指定的 8 位无符号整数转换为等价的 double 精度浮点数。

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) 方法

将指定的 8 位有符号整数转换为等价的 double 精度浮点数。

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) 方法

将指定的 16 位无符号整数转换为等价的 double 精度浮点数。

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) 方法

将指定的 16 位有符号整数转换为等价的 double 精度浮点数。

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) 方法

将指定的 32 位无符号整数转换为等价的 double 精度浮点数。

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) 方法

将指定的 32 位有符号整数转换为等价的 double 精度浮点数。

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) 方法

将指定的 64 位无符号整数转换为等价的 double 精度浮点数。

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) 方法

将指定的 64 位有符号整数转换为等价的 double 精度浮点数。

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) 方法

将指定的单精度数转换为等价的 double 精度浮点数。

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) 方法

返回指定的 double 数字。

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) 方法

将指定的 decimal 数字转换为等价的 double 精度浮点数。

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) 方法

不支持转换。始终抛出 InvalidCastException。

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) 方法

不支持转换。始终抛出 InvalidCastException。

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) 方法

将指定的空字符串转换为等价的 double 精度浮点值。

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```

### 返回值

零。

## Convert::ToDouble(const char_t *) 方法

将包含数字字符串表示的 c-string 转换为等价的 double 精度浮点值。

```cpp
static double System::Convert::ToDouble(const char_t *value)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | The c-string to convert |

### 返回值

等价于指定 c-string 表示的数字的 double 精度浮点值

## Convert::ToDouble(const String\&) 方法

将包含数字字符串表示的 string 转换为等价的 double 精度浮点值。

```cpp
static double System::Convert::ToDouble(const String &value)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |

### 返回值

等价于指定字符串表示的数字的 double 精度浮点值

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息，将包含数字字符串表示的 string 转换为等价的 double 精度浮点值。

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information |

### 返回值

等价于指定字符串表示的数字的 double 精度浮点值

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) 方法




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息和数字样式，将包含数字字符串表示的 string 转换为等价的 double 精度浮点值。

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information |

### 返回值

等价于指定字符串表示的数字的 double 精度浮点值

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

将指定的装箱值转换为 double 精度浮点值。如果装箱值的类型是 [String](../../string/)，则在转换期间使用指定的字符串格式。

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | The shared pointer to the object boxing the value to convert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | The string format to be used if the type of the boxed value is [String](../../string/) |

### 返回值

等价于指定装箱值的 double 精度浮点值

## 另请参见

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)