---
title: ToSByte()
second_title: Aspose.Slides C++ API 参考
description: 将指定的布尔值转换为等效的 8 位有符号整数。
type: docs
weight: 105
url: /zh/system/convert/tosbyte/
---
## Convert::ToSByte(bool) 方法

将指定的布尔值转换为等效的 8 位有符号整数。

```cpp
static constexpr int8_t System::Convert::ToSByte(bool value)
```

## Convert::ToSByte(uint8_t) 方法

将指定的 8 位无符号整数转换为等效的 8 位有符号整数。

```cpp
static int8_t System::Convert::ToSByte(uint8_t value)
```

## Convert::ToSByte(int8_t) 方法

返回指定的 8 位有符号整数。

```cpp
static constexpr int8_t System::Convert::ToSByte(int8_t value)
```

## Convert::ToSByte(uint16_t) 方法

将指定的 16 位无符号整数转换为等效的 8 位有符号整数。

```cpp
static int8_t System::Convert::ToSByte(uint16_t value)
```

## Convert::ToSByte(int16_t) 方法

将指定的 16 位有符号整数转换为等效的 8 位有符号整数。

```cpp
static int8_t System::Convert::ToSByte(int16_t value)
```

## Convert::ToSByte(uint32_t) 方法

将指定的 32 位无符号整数转换为等效的 8 位有符号整数。

```cpp
static int8_t System::Convert::ToSByte(uint32_t value)
```

## Convert::ToSByte(int32_t) 方法

将指定的 32 位有符号整数转换为等效的 8 位有符号整数。

```cpp
static int8_t System::Convert::ToSByte(int32_t value)
```

## Convert::ToSByte(uint64_t) 方法

将指定的 64 位无符号整数转换为等效的 8 位有符号整数。

```cpp
static int8_t System::Convert::ToSByte(uint64_t value)
```

## Convert::ToSByte(int64_t) 方法

将指定的 64 位有符号整数转换为等效的 8 位有符号整数。

```cpp
static int8_t System::Convert::ToSByte(int64_t value)
```

## Convert::ToSByte(float) 方法

将指定的 float 数字转换为等效的 8 位有符号整数。

```cpp
static int8_t System::Convert::ToSByte(float value)
```

## Convert::ToSByte(double) 方法

将指定的 double 数字转换为等效的 8 位有符号整数。

```cpp
static int8_t System::Convert::ToSByte(double value)
```

## Convert::ToSByte(const Decimal\&) 方法

将指定的十进制数字转换为等效的 8 位有符号整数。

```cpp
static int8_t System::Convert::ToSByte(const Decimal &value)
```

## Convert::ToSByte(char_t) 方法

将指定的 Unicode 字符转换为等效的 8 位有符号整数。

```cpp
static int8_t System::Convert::ToSByte(char_t value)
```

## Convert::ToSByte(DateTime) 方法

不支持此转换。始终抛出 InvalidCastException。

```cpp
static int8_t System::Convert::ToSByte(DateTime value)
```

## Convert::ToSByte(std::nullptr_t) 方法

将指定的空字符串转换为等效的 8 位整数值。

```cpp
static constexpr int8_t System::Convert::ToSByte(std::nullptr_t)
```

### 返回值

零。

## Convert::ToSByte(const char_t *) 方法

将包含数字字符串表示的 c 字符串转换为等效的 8 位整数值。

```cpp
static int8_t System::Convert::ToSByte(const char_t *value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要转换的 c 字符串 |

### 返回值

等于指定 c 字符串所表示数字的 8 位整数值。

## Convert::ToSByte(const String\&) 方法

将包含数字字符串表示的 string 转换为等效的 8 位整数值。

```cpp
static int8_t System::Convert::ToSByte(const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |

### 返回值

等于指定字符串所表示数字的 8 位整数值。

## Convert::ToSByte(const String\&, int) 方法

将包含指定基数数字字符串表示的 string 转换为等效的 8 位整数值。

```cpp
static int8_t System::Convert::ToSByte(const String &value, int from_base)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| from_base | int | 字符串表示的数字的基数 |

### 返回值

等于指定字符串所表示数字的 8 位整数值。

## Convert::ToSByte(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息，将包含数字字符串表示的 string 转换为等效的无符号 8 位整数值。

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字符串格式信息的对象的指针 |

### 返回值

等于指定字符串所表示数字的 8 位整数值。

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, std::nullptr_t) 方法




```cpp
static int8_t System::Convert::ToSByte(const String &value, std::nullptr_t)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息和数字样式，将包含数字字符串表示的 string 转换为等效的 8 位整数值。

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 枚举值的按位组合，指定数字字符串表示允许的样式 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字符串格式信息的对象的指针 |

### 返回值

等于指定字符串所表示数字的无符号 8 位整数值。

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSByte(Enum) 方法




```cpp
template<typename Enum,typename> static int8_t System::Convert::ToSByte(Enum value)
```

## Convert::ToSByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

将指定的装箱值转换为等效的 8 位整数值。

```cpp
static int8_t System::Convert::ToSByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 装箱值所在对象的共享指针 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 如果装箱值的类型是 [String](../../string/)，则使用的字符串格式 |

### 返回值

等价于指定装箱值的 8 位整数值。

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