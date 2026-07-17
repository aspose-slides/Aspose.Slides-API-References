---
title: ToUInt32()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的布尔值转换为等效的 32 位无符号整数。
type: docs
weight: 170
url: /zh/system/convert/touint32/
---
## Convert::ToUInt32(bool) 方法

将指定的布尔值转换为等效的 32 位无符号整数。

```cpp
static constexpr uint32_t System::Convert::ToUInt32(bool value)
```

## Convert::ToUInt32(uint8_t) 方法

将指定的 uint8_t 转换为等效的 32 位无符号整数。

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint8_t value)
```

## Convert::ToUInt32(int8_t) 方法

将指定的 int8_t 转换为等效的 32 位无符号整数。

```cpp
static uint32_t System::Convert::ToUInt32(int8_t value)
```

## Convert::ToUInt32(uint16_t) 方法

将指定的 uint16_t 转换为等效的 32 位无符号整数。

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint16_t value)
```

## Convert::ToUInt32(int16_t) 方法

将指定的 int16_t 转换为等效的 32 位无符号整数。

```cpp
static uint32_t System::Convert::ToUInt32(int16_t value)
```

## Convert::ToUInt32(uint32_t) 方法

返回指定的 32 位无符号整数。

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint32_t value)
```

## Convert::ToUInt32(int32_t) 方法

将指定的 int32_t 转换为等效的 32 位无符号整数。

```cpp
static uint32_t System::Convert::ToUInt32(int32_t value)
```

## Convert::ToUInt32(uint64_t) 方法

将指定的 uint64_t 转换为等效的 32 位无符号整数。

```cpp
static uint32_t System::Convert::ToUInt32(uint64_t value)
```

## Convert::ToUInt32(int64_t) 方法

将指定的 int64_t 转换为等效的 32 位无符号整数。

```cpp
static uint32_t System::Convert::ToUInt32(int64_t value)
```

## Convert::ToUInt32(float) 方法

将指定的 float 数转换为等效的 32 位无符号整数。

```cpp
static uint32_t System::Convert::ToUInt32(float value)
```

## Convert::ToUInt32(double) 方法

将指定的 double 数转换为等效的 32 位无符号整数。

```cpp
static uint32_t System::Convert::ToUInt32(double value)
```

## Convert::ToUInt32(const Decimal\&) 方法

将指定的 Decimal 数字转换为等效的 32 位无符号整数。

```cpp
static uint32_t System::Convert::ToUInt32(const Decimal &value)
```

## Convert::ToUInt32(char_t) 方法

将指定的 char_t 字符转换为等效的 32 位无符号整数。

```cpp
static constexpr uint32_t System::Convert::ToUInt32(char_t value)
```

## Convert::ToUInt32(DateTime) 方法

不支持转换。始终抛出 InvalidCastException。

```cpp
static uint32_t System::Convert::ToUInt32(DateTime value)
```

## Convert::ToUInt32(std::nullptr_t) 方法

将指定的空字符串转换为等效的 32 位无符号整数值。

```cpp
static constexpr uint32_t System::Convert::ToUInt32(std::nullptr_t)
```

### 返回值

零。

## Convert::ToUInt32(const char_t *) 方法

将包含数字字符串表示的指定 c 字符串转换为等效的 32 位无符号整数值。

```cpp
static uint32_t System::Convert::ToUInt32(const char_t *value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要转换的 c 字符串 |

### 返回值

等于指定 c 字符串所表示数字的 32 位无符号整数值

## Convert::ToUInt32(const String\&) 方法

将包含数字字符串表示的指定字符串转换为等效的 32 位无符号整数值。

```cpp
static uint32_t System::Convert::ToUInt32(const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |

### 返回值

等于指定字符串所表示数字的 32 位无符号整数值

## Convert::ToUInt32(const String\&, int) 方法

将包含在指定基数下的数字字符串表示的指定字符串转换为等效的 32 位无符号整数值。

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, int from_base)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| from_base | int | 字符串所表示数字的基数 |

### 返回值

等于指定字符串所表示数字的 32 位无符号整数值

## Convert::ToUInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

将指定字符串转换为等效的 32 位无符号整数值，使用提供的格式信息。

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字符串格式信息的对象的指针 |

### 返回值

等于指定字符串所表示数字的 32 位无符号整数值

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, std::nullptr_t) 方法




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, std::nullptr_t)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

将指定字符串转换为等效的 32 位无符号整数值，使用提供的格式信息和数字样式。

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 枚举值的位组合，用于指定数字字符串表示的允许样式 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字符串格式信息的对象的指针 |

### 返回值

等于指定字符串所表示数字的 32 位无符号整数值

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt32(Enum) 方法




```cpp
template<typename Enum,typename> static uint32_t System::Convert::ToUInt32(Enum value)
```

## Convert::ToUInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

将指定的装箱值转换为等效的 32 位无符号整数值。

```cpp
static uint32_t System::Convert::ToUInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 指向装箱待转换值的对象的共享指针 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 如果装箱值的类型是 [String](../../string/)，则使用的字符串格式 |

### 返回值

等价于指定装箱值的 32 位无符号整数值

## 参见

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