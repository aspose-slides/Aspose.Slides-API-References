---
title: ToUInt64()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的布尔值转换为等效的 64 位无符号整数。
type: docs
weight: 196
url: /zh/system/convert/touint64/
---
## Convert::ToUInt64(bool) 方法

将指定的布尔值转换为等效的 64 位无符号整数。

```cpp
static constexpr uint64_t System::Convert::ToUInt64(bool value)
```
## Convert::ToUInt64(uint8_t) 方法

将指定的 8 位无符号整数转换为等效的 64 位无符号整数。

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint8_t value)
```
## Convert::ToUInt64(int8_t) 方法

将指定的 8 位有符号整数转换为等效的 64 位无符号整数。

```cpp
static uint64_t System::Convert::ToUInt64(int8_t value)
```
## Convert::ToUInt64(uint16_t) 方法

将指定的 16 位无符号整数转换为等效的 64 位无符号整数。

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint16_t value)
```
## Convert::ToUInt64(int16_t) 方法

将指定的 16 位有符号整数转换为等效的 64 位无符号整数。

```cpp
static uint64_t System::Convert::ToUInt64(int16_t value)
```
## Convert::ToUInt64(uint32_t) 方法

将指定的 32 位无符号整数转换为等效的 64 位无符号整数。

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint32_t value)
```
## Convert::ToUInt64(int32_t) 方法

将指定的 32 位有符号整数转换为等效的 64 位无符号整数。

```cpp
static uint64_t System::Convert::ToUInt64(int32_t value)
```
## Convert::ToUInt64(uint64_t) 方法

返回指定的 64 位无符号整数。

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint64_t value)
```
## Convert::ToUInt64(int64_t) 方法

将指定的 64 位有符号整数转换为等效的 64 位无符号整数。

```cpp
static uint64_t System::Convert::ToUInt64(int64_t value)
```
## Convert::ToUInt64(float) 方法

将指定的单精度浮点数转换为等效的 64 位无符号整数。

```cpp
static uint64_t System::Convert::ToUInt64(float value)
```
## Convert::ToUInt64(double) 方法

将指定的双精度浮点数转换为等效的 64 位无符号整数。

```cpp
static uint64_t System::Convert::ToUInt64(double value)
```
## Convert::ToUInt64(const Decimal\&) 方法

将指定的十进制数转换为等效的 64 位无符号整数。

```cpp
static uint64_t System::Convert::ToUInt64(const Decimal &value)
```
## Convert::ToUInt64(char_t) 方法

将指定的 Unicode 字符转换为等效的 64 位无符号整数。

```cpp
static constexpr uint64_t System::Convert::ToUInt64(char_t value)
```
## Convert::ToUInt64(DateTime) 方法

不支持转换。始终抛出 InvalidCastException。

```cpp
static uint64_t System::Convert::ToUInt64(DateTime value)
```
## Convert::ToUInt64(std::nullptr_t) 方法

将指定的空字符串转换为等效的 64 位无符号整数值。

```cpp
static constexpr uint64_t System::Convert::ToUInt64(std::nullptr_t)
```


### 返回值

零。

## Convert::ToUInt64(const char_t *) 方法

将包含数字字符串表示的指定 c 字符串转换为等效的 64 位无符号整数值。

```cpp
static uint64_t System::Convert::ToUInt64(const char_t *value)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要转换的 c 字符串 |

### 返回值

等于指定 c 字符串所表示数字的 64 位无符号整数值

## Convert::ToUInt64(const String\&) 方法

将包含数字字符串表示的指定字符串转换为等效的 64 位无符号整数值。

```cpp
static uint64_t System::Convert::ToUInt64(const String &value)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |

### 返回值

等于指定字符串所表示数字的 64 位无符号整数值

## Convert::ToUInt64(const String\&, int) 方法

将包含指定进制数字字符串表示的指定字符串转换为等效的 64 位无符号整数值。

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, int from_base)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| from_base | int | 字符串中数字的进制 |

### 返回值

等于指定字符串所表示数字的 64 位无符号整数值

## Convert::ToUInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息将包含数字字符串表示的指定字符串转换为等效的 64 位无符号整数值。

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字符串格式信息的对象指针 |

### 返回值

等于指定字符串所表示数字的 64 位无符号整数值

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, std::nullptr_t) 方法




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, std::nullptr_t)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息和数字样式将包含数字字符串表示的指定字符串转换为等效的 64 位无符号整数值。

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 枚举值的按位组合，指定数字字符串表示的允许样式 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字符串格式信息的对象指针 |

### 返回值

等于指定字符串所表示数字的 64 位无符号整数值

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt64(Enum) 方法




```cpp
template<typename Enum,typename> static uint64_t System::Convert::ToUInt64(Enum value)
```

## Convert::ToUInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

将指定的装箱值转换为等效的 64 位无符号整数值。

```cpp
static uint64_t System::Convert::ToUInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 装箱值对象的共享指针 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 如果装箱值的类型为 [String](../../string/)，要使用的字符串格式 |

### 返回值

等效于指定装箱值的 64 位无符号整数值

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
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)