---
title: ToUInt16()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的布尔值转换为等效的 16 位无符号整数。
type: docs
weight: 144
url: /zh/system/convert/touint16/
---
## Convert::ToUInt16(bool) 方法

将指定的布尔值转换为等效的 16 位无符号整数。

```cpp
static constexpr uint16_t System::Convert::ToUInt16(bool value)
```
## Convert::ToUInt16(uint8_t) 方法

将指定的 8 位无符号整数转换为等效的 16 位无符号整数。

```cpp
static constexpr uint16_t System::Convert::ToUInt16(uint8_t value)
```
## Convert::ToUInt16(int8_t) 方法

将指定的 8 位有符号整数转换为等效的 16 位无符号整数。

```cpp
static uint16_t System::Convert::ToUInt16(int8_t value)
```
## Convert::ToUInt16(uint16_t) 方法

返回指定的 16 位无符号整数。

```cpp
static constexpr uint16_t System::Convert::ToUInt16(uint16_t value)
```
## Convert::ToUInt16(int16_t) 方法

将指定的 16 位有符号整数转换为等效的 16 位无符号整数。

```cpp
static uint16_t System::Convert::ToUInt16(int16_t value)
```
## Convert::ToUInt16(uint32_t) 方法

将指定的 32 位无符号整数转换为等效的 16 位无符号整数。

```cpp
static uint16_t System::Convert::ToUInt16(uint32_t value)
```
## Convert::ToUInt16(int32_t) 方法

将指定的 32 位有符号整数转换为等效的 16 位无符号整数。

```cpp
static uint16_t System::Convert::ToUInt16(int32_t value)
```
## Convert::ToUInt16(uint64_t) 方法

将指定的 64 位无符号整数转换为等效的 16 位无符号整数。

```cpp
static uint16_t System::Convert::ToUInt16(uint64_t value)
```
## Convert::ToUInt16(int64_t) 方法

将指定的 64 位有符号整数转换为等效的 16 位无符号整数。

```cpp
static uint16_t System::Convert::ToUInt16(int64_t value)
```
## Convert::ToUInt16(float) 方法

将指定的浮点数转换为等效的 16 位无符号整数。

```cpp
static uint16_t System::Convert::ToUInt16(float value)
```
## Convert::ToUInt16(double) 方法

将指定的双精度数转换为等效的 16 位无符号整数。

```cpp
static uint16_t System::Convert::ToUInt16(double value)
```
## Convert::ToUInt16(const Decimal\&) 方法

将指定的十进制数转换为等效的 16 位无符号整数。

```cpp
static uint16_t System::Convert::ToUInt16(const Decimal &value)
```
## Convert::ToUInt16(char_t) 方法

将指定的 Unicode 字符转换为等效的 16 位无符号整数。

```cpp
static constexpr uint16_t System::Convert::ToUInt16(char_t value)
```
## Convert::ToUInt16(DateTime) 方法

不支持此转换。始终抛出 InvalidCastException。

```cpp
static uint16_t System::Convert::ToUInt16(DateTime value)
```
## Convert::ToUInt16(std::nullptr_t) 方法

将指定的空字符串转换为等效的 16 位无符号整数值。

```cpp
static constexpr uint16_t System::Convert::ToUInt16(std::nullptr_t)
```

### 返回值

Zero.

## Convert::ToUInt16(const char_t *) 方法

将包含数字字符串表示的 c 字符串转换为等效的 16 位无符号整数值。

```cpp
static uint16_t System::Convert::ToUInt16(const char_t *value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要转换的 c 字符串 |

### 返回值

等于指定 c 字符串所表示数字的 16 位无符号整数值

## Convert::ToUInt16(const String\&) 方法

将包含数字字符串表示的字符串转换为等效的 16 位无符号整数值。

```cpp
static uint16_t System::Convert::ToUInt16(const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |

### 返回值

等于指定字符串所表示数字的 16 位无符号整数值

## Convert::ToUInt16(const String\&, int) 方法

将包含指定基数的数字字符串表示的字符串转换为等效的 16 位无符号整数值。

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, int from_base)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| from_base | int | 字符串所表示数字的基数 |

### 返回值

等于指定字符串所表示数字的 16 位无符号整数值

## Convert::ToUInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息将包含数字字符串表示的字符串转换为等效的 16 位无符号整数值。

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字符串格式信息的对象指针 |

### 返回值

等于指定字符串所表示数字的 16 位无符号整数值

## Convert::ToUInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt16(const String\&, std::nullptr_t) 方法




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, std::nullptr_t)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息和数字样式将包含数字字符串表示的字符串转换为等效的 16 位无符号整数值。

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 枚举值的位组合，指定数字字符串表示的允许样式 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字符串格式信息的对象指针 |

### 返回值

等于指定字符串所表示数字的 16 位无符号整数值

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt16(Enum) 方法




```cpp
template<typename Enum,typename> static uint16_t System::Convert::ToUInt16(Enum value)
```

## Convert::ToUInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

将指定的装箱值转换为等效的 16 位无符号整数值。

```cpp
static uint16_t System::Convert::ToUInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 装箱了待转换值的对象的共享指针 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 当装箱值的类型为 [String](../../string/) 时使用的字符串格式 |

### 返回值

等效于指定装箱值的 16 位无符号整数值

## 另见

* 枚举 [NumberStyles](../../../system.globalization/numberstyles/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [Decimal](../../decimal/)
* 类 [DateTime](../../datetime/)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 类 [Object](../../object/)
* 结构 [Convert](../)
* 结构 [Enum](../../enum/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)