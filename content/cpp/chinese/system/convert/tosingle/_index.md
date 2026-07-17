---
title: ToSingle()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的布尔值转换为等效的单精度浮点数。
type: docs
weight: 209
url: /zh/system/convert/tosingle/
---
## Convert::ToSingle(bool) 方法

将指定的布尔值转换为等效的单精度浮点数。

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```

## Convert::ToSingle(uint8_t) 方法

将指定的 8 位无符号整数转换为等效的单精度浮点数。

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```

## Convert::ToSingle(int8_t) 方法

将指定的 8 位有符号整数转换为等效的单精度浮点数。

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```

## Convert::ToSingle(uint16_t) 方法

将指定的 16 位无符号整数转换为等效的单精度浮点数。

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```

## Convert::ToSingle(int16_t) 方法

将指定的 16 位有符号整数转换为等效的单精度浮点数。

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```

## Convert::ToSingle(uint32_t) 方法

将指定的 32 位无符号整数转换为等效的单精度浮点数。

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```

## Convert::ToSingle(int32_t) 方法

将指定的 32 位有符号整数转换为等效的单精度浮点数。

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```

## Convert::ToSingle(uint64_t) 方法

将指定的 64 位无符号整数转换为等效的单精度浮点数。

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```

## Convert::ToSingle(int64_t) 方法

将指定的 64 位有符号整数转换为等效的单精度浮点数。

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```

## Convert::ToSingle(float) 方法

返回指定的 float 数值。

```cpp
static constexpr float System::Convert::ToSingle(float value)
```

## Convert::ToSingle(double) 方法

将指定的双精度数值转换为等效的单精度浮点数。

```cpp
static constexpr float System::Convert::ToSingle(double value)
```

## Convert::ToSingle(const Decimal&) 方法

将指定的十进制数值转换为等效的单精度浮点数。

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```

## Convert::ToSingle(char_t) 方法

不支持此转换。始终抛出 InvalidCastException。

```cpp
static float System::Convert::ToSingle(char_t value)
```

## Convert::ToSingle(DateTime) 方法

不支持此转换。始终抛出 InvalidCastException。

```cpp
static float System::Convert::ToSingle(DateTime value)
```

## Convert::ToSingle(std::nullptr_t) 方法

将指定的空字符串转换为等效的单精度浮点值。

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```

### 返回值

Zero.

## Convert::ToSingle(const char_t *) 方法

将包含数值字符串表示的 c 字符串转换为等效的单精度浮点值。

```cpp
static float System::Convert::ToSingle(const char_t *value)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | 要转换的 c 字符串 |

### 返回值

等于指定 c 字符串所表示数值的单精度浮点值

## Convert::ToSingle(const String&) 方法

将包含数值字符串表示的字符串转换为等效的单精度浮点值。

```cpp
static float System::Convert::ToSingle(const String &value)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |

### 返回值

等于指定字符串所表示数值的单精度浮点值

## Convert::ToSingle(const String&, const SharedPtr<IFormatProvider>&) 方法

使用提供的格式信息将包含数值字符串表示的字符串转换为等效的单精度浮点值。

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字符串格式信息的对象指针 |

### 返回值

等于指定字符串所表示数值的单精度浮点值

## Convert::ToSingle(const String&, const SharedPtr<Globalization::CultureInfo>&) 方法




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String&, const SharedPtr<Globalization::NumberFormatInfo>&) 方法




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String&, std::nullptr_t) 方法




```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String&, Globalization::NumberStyles, const SharedPtr<IFormatProvider>&) 方法

使用提供的格式信息和数字样式将包含数值字符串表示的字符串转换为等效的单精度浮点值。

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 枚举值的按位组合，指定允许的数字字符串表示样式 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字符串格式信息的对象指针 |

### 返回值

等于指定字符串所表示数值的单精度浮点值

## Convert::ToSingle(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::CultureInfo>&) 方法




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::NumberFormatInfo>&) 方法




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String&, Globalization::NumberStyles, std::nullptr_t) 方法 




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr<Object>&, const SharedPtr<IFormatProvider>&) 方法

将指定的装箱值转换为单精度浮点值。

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 装箱要转换的值的对象的共享指针 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 如果装箱值的类型为 [String](../../string/)，使用的字符串格式 |

### 返回值

等效于指定装箱值的单精度浮点值

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
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)