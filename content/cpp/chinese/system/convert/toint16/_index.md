---
title: ToInt16()
second_title: Aspose.Slides C++ API 参考
description: 将指定的布尔值转换为等效的 16 位有符号整数。
type: docs
weight: 131
url: /zh/system/convert/toint16/
---
## Convert::ToInt16(bool) 方法

将指定的布尔值转换为等效的 16 位有符号整数。

```cpp
static constexpr int16_t System::Convert::ToInt16(bool value)
```

## Convert::ToInt16(uint8_t) 方法

将指定的 8 位无符号整数转换为等效的 16 位有符号整数。

```cpp
static constexpr int16_t System::Convert::ToInt16(uint8_t value)
```

## Convert::ToInt16(int8_t) 方法

将指定的 8 位有符号整数转换为等效的 16 位有符号整数。

```cpp
static constexpr int16_t System::Convert::ToInt16(int8_t value)
```

## Convert::ToInt16(uint16_t) 方法

将指定的 16 位无符号整数转换为等效的 16 位有符号整数。

```cpp
static int16_t System::Convert::ToInt16(uint16_t value)
```

## Convert::ToInt16(int16_t) 方法

返回指定的 16 位有符号整数。

```cpp
static constexpr int16_t System::Convert::ToInt16(int16_t value)
```

## Convert::ToInt16(uint32_t) 方法

将指定的 32 位无符号整数转换为等效的 16 位有符号整数。

```cpp
static int16_t System::Convert::ToInt16(uint32_t value)
```

## Convert::ToInt16(int32_t) 方法

将指定的 32 位有符号整数转换为等效的 16 位有符号整数。

```cpp
static int16_t System::Convert::ToInt16(int32_t value)
```

## Convert::ToInt16(uint64_t) 方法

将指定的 64 位无符号整数转换为等效的 16 位有符号整数。

```cpp
static int16_t System::Convert::ToInt16(uint64_t value)
```

## Convert::ToInt16(int64_t) 方法

将指定的 64 位有符号整数转换为等效的 16 位有符号整数。

```cpp
static int16_t System::Convert::ToInt16(int64_t value)
```

## Convert::ToInt16(float) 方法

将指定的浮点数转换为等效的 16 位有符号整数。

```cpp
static int16_t System::Convert::ToInt16(float value)
```

## Convert::ToInt16(double) 方法

将指定的双精度数转换为等效的 16 位有符号整数。

```cpp
static int16_t System::Convert::ToInt16(double value)
```

## Convert::ToInt16(const Decimal\&) 方法

将指定的十进制数转换为等效的 16 位有符号整数。

```cpp
static int16_t System::Convert::ToInt16(const Decimal &value)
```

## Convert::ToInt16(char_t) 方法

将指定的 Unicode 字符转换为等效的 16 位有符号整数。

```cpp
static int16_t System::Convert::ToInt16(char_t value)
```

## Convert::ToInt16(DateTime) 方法

不支持转换。始终抛出 InvalidCastException。

```cpp
static int16_t System::Convert::ToInt16(DateTime value)
```

## Convert::ToInt16(std::nullptr_t) 方法

将指定的空字符串转换为等效的 16 位整数值。

```cpp
static constexpr int16_t System::Convert::ToInt16(std::nullptr_t)
```

### 返回值

零。

## Convert::ToInt16(const char_t *) 方法

将包含数字字符串表示形式的指定 C 字符串转换为等效的 16 位整数值。

```cpp
static int16_t System::Convert::ToInt16(const char_t *value)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | const char_t * | 要转换的 C 字符串 |

### 返回值

等于指定 C 字符串所表示数字的 16 位整数值

## Convert::ToInt16(const String\&) 方法

将包含数字字符串表示形式的指定字符串转换为等效的 16 位整数值。

```cpp
static int16_t System::Convert::ToInt16(const String &value)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |

### 返回值

等于指定字符串所表示数字的 16 位整数值

## Convert::ToInt16(const String\&, int) 方法

将包含指定基数的数字字符串表示形式的指定字符串转换为等效的 16 位整数值。

```cpp
static int16_t System::Convert::ToInt16(const String &value, int from_base)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| from_base | int | 字符串所表示数字的基数 |

### 返回值

等于指定字符串所表示数字的 16 位整数值

## Convert::ToInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息将包含数字字符串表示形式的指定字符串转换为等效的 16 位整数值。

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字符串格式信息的对象的指针 |

### 返回值

等于指定字符串所表示数字的 16 位整数值

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, std::nullptr_t) 方法

```cpp
static int16_t System::Convert::ToInt16(const String &value, std::nullptr_t)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息和数字样式将包含数字字符串表示形式的指定字符串转换为等效的 16 位整数值。

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 枚举值的位组合，指定允许的数字字符串表示形式的样式 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字符串格式信息的对象的指针 |

### 返回值

等于指定字符串所表示数字的 16 位整数值

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt16(Enum) 方法

```cpp
template<typename Enum,typename> static int16_t System::Convert::ToInt16(Enum value)
```

## Convert::ToInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

将指定的装箱值转换为等效的 16 位整数值。

```cpp
static int16_t System::Convert::ToInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 指向装箱要转换值的对象的共享指针 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 如果装箱值的类型是 [String](../../string/)，则使用的字符串格式 |

### 返回值

等同于指定装箱值的 16 位整数值

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