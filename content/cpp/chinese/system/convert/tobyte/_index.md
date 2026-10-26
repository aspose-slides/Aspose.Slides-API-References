---
title: ToByte()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的布尔值转换为等价的 8 位无符号整数。
type: docs
weight: 92
url: /zh/system/convert/tobyte/
---
## Convert::ToByte(bool) 方法

将指定的布尔值转换为等价的 8 位无符号整数。

```cpp
static constexpr uint8_t System::Convert::ToByte(bool value)
```

## Convert::ToByte(uint8_t) 方法

返回指定的 8 位无符号整数。

```cpp
static constexpr uint8_t System::Convert::ToByte(uint8_t value)
```

## Convert::ToByte(int8_t) 方法

将指定的 8 位有符号整数转换为等价的 8 位无符号整数。

```cpp
static uint8_t System::Convert::ToByte(int8_t value)
```

## Convert::ToByte(uint16_t) 方法

将指定的 16 位无符号整数转换为等价的 8 位无符号整数。

```cpp
static uint8_t System::Convert::ToByte(uint16_t value)
```

## Convert::ToByte(int16_t) 方法

将指定的 16 位有符号整数转换为等价的 8 位无符号整数。

```cpp
static uint8_t System::Convert::ToByte(int16_t value)
```

## Convert::ToByte(uint32_t) 方法

将指定的 32 位无符号整数转换为等价的 8 位无符号整数。

```cpp
static uint8_t System::Convert::ToByte(uint32_t value)
```

## Convert::ToByte(int32_t) 方法

将指定的 32 位有符号整数转换为等价的 8 位无符号整数。

```cpp
static uint8_t System::Convert::ToByte(int32_t value)
```

## Convert::ToByte(uint64_t) 方法

将指定的 64 位无符号整数转换为等价的 8 位无符号整数。

```cpp
static uint8_t System::Convert::ToByte(uint64_t value)
```

## Convert::ToByte(int64_t) 方法

将指定的 64 位有符号整数转换为等价的 8 位无符号整数。

```cpp
static uint8_t System::Convert::ToByte(int64_t value)
```

## Convert::ToByte(float) 方法

将指定的 float 数字转换为等价的 8 位无符号整数。

```cpp
static uint8_t System::Convert::ToByte(float value)
```

## Convert::ToByte(double) 方法

将指定的 double 数字转换为等价的 8 位无符号整数。

```cpp
static uint8_t System::Convert::ToByte(double value)
```

## Convert::ToByte(const Decimal\&) 方法

将指定的十进制数字转换为等价的 8 位无符号整数。

```cpp
static uint8_t System::Convert::ToByte(const Decimal &value)
```

## Convert::ToByte(char_t) 方法

将指定的 Unicode 字符转换为等价的 8 位无符号整数。

```cpp
static uint8_t System::Convert::ToByte(char_t value)
```

## Convert::ToByte(DateTime) 方法

不支持转换。始终抛出 InvalidCastException。

```cpp
static uint8_t System::Convert::ToByte(DateTime value)
```

## Convert::ToByte(std::nullptr_t) 方法

将指定的空字符串转换为等价的无符号 8 位整数值。

```cpp
static constexpr uint8_t System::Convert::ToByte(std::nullptr_t)
```

### 返回值

零。

## Convert::ToByte(const char_t *) 方法

将包含数字字符串表示的指定 c-string 转换为等价的无符号 8 位整数值。

```cpp
static uint8_t System::Convert::ToByte(const char_t *value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要转换的 c-string |

### 返回值

等于指定 c-string 所表示数字的无符号 8 位整数值

## Convert::ToByte(const String\&) 方法

将包含数字字符串表示的指定字符串转换为等价的无符号 8 位整数值。

```cpp
static uint8_t System::Convert::ToByte(const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |

### 返回值

等于指定字符串所表示数字的无符号 8 位整数值

## Convert::ToByte(const String\&, int) 方法

将包含数字字符串表示且使用指定进制的字符串转换为等价的无符号 8 位整数值。

```cpp
static uint8_t System::Convert::ToByte(const String &value, int from_base)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| from_base | int | 字符串所表示数字的进制 |

### 返回值

等于指定字符串所表示数字的无符号 8 位整数值

## Convert::ToByte(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息，将包含数字字符串表示的指定字符串转换为等价的无符号 8 位整数值。

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字符串格式信息的对象的指针 |

### 返回值

等于指定字符串所表示数字的无符号 8 位整数值

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, std::nullptr_t) 方法

```cpp
static uint8_t System::Convert::ToByte(const String &value, std::nullptr_t)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息和数字样式，将包含数字字符串表示的指定字符串转换为等价的无符号 8 位整数值。

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum 的值的按位组合，指定数字字符串表示的允许样式 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字符串格式信息的对象的指针 |

### 返回值

等于指定字符串所表示数字的无符号 8 位整数值

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToByte(Enum) 方法

```cpp
template<typename Enum,typename> static uint8_t System::Convert::ToByte(Enum value)
```

## Convert::ToByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

将指定的装箱值转换为等价的无符号 8 位整数值。

```cpp
static uint8_t System::Convert::ToByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 装箱了待转换值的对象的共享指针 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 当装箱值的类型为 [String](../../string/) 时使用的字符串格式 |

### 返回值

等价于指定装箱值的无符号 8 位整数值

## 另请参阅

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
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)