---
title: ToInt32()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的布尔值转换为等效的 32 位有符号整数。
type: docs
weight: 157
url: /zh/system/convert/toint32/
---
## Convert::ToInt32(bool) 方法

将指定的布尔值转换为等效的 32 位有符号整数。

```cpp
static constexpr int System::Convert::ToInt32(bool value)
```
## Convert::ToInt32(uint8_t) 方法

将指定的 8 位无符号整数转换为等效的 32 位有符号整数。

```cpp
static constexpr int System::Convert::ToInt32(uint8_t value)
```
## Convert::ToInt32(int8_t) 方法

将指定的 8 位有符号整数转换为等效的 32 位有符号整数。

```cpp
static constexpr int System::Convert::ToInt32(int8_t value)
```
## Convert::ToInt32(uint16_t) 方法

将指定的 16 位无符号整数转换为等效的 32 位有符号整数。

```cpp
static constexpr int System::Convert::ToInt32(uint16_t value)
```
## Convert::ToInt32(int16_t) 方法

将指定的 16 位有符号整数转换为等效的 32 位有符号整数。

```cpp
static constexpr int System::Convert::ToInt32(int16_t value)
```
## Convert::ToInt32(uint32_t) 方法

将指定的 32 位无符号整数转换为等效的 32 位有符号整数。

```cpp
static int System::Convert::ToInt32(uint32_t value)
```
## Convert::ToInt32(int32_t) 方法

返回指定的 32 位有符号整数。

```cpp
static constexpr int System::Convert::ToInt32(int32_t value)
```
## Convert::ToInt32(uint64_t) 方法

将指定的 64 位无符号整数转换为等效的 32 位有符号整数。

```cpp
static int System::Convert::ToInt32(uint64_t value)
```
## Convert::ToInt32(int64_t) 方法

将指定的 64 位有符号整数转换为等效的 32 位有符号整数。

```cpp
static int System::Convert::ToInt32(int64_t value)
```
## Convert::ToInt32(float) 方法

将指定的单精度浮点数转换为等效的 32 位有符号整数。

```cpp
static int System::Convert::ToInt32(float value)
```
## Convert::ToInt32(double) 方法

将指定的双精度浮点数转换为等效的 32 位有符号整数。

```cpp
static int System::Convert::ToInt32(double value)
```
## Convert::ToInt32(const Decimal\&) 方法

将指定的十进制数转换为等效的 32 位有符号整数。

```cpp
static int System::Convert::ToInt32(const Decimal &value)
```
## Convert::ToInt32(char_t) 方法

将指定的 Unicode 字符转换为等效的 32 位有符号整数。

```cpp
static constexpr int System::Convert::ToInt32(char_t value)
```
## Convert::ToInt32(DateTime) 方法

不支持此转换。始终抛出 InvalidCastException。

```cpp
static int System::Convert::ToInt32(DateTime value)
```
## Convert::ToInt32(std::nullptr_t) 方法

将指定的空字符串转换为等效的 32 位整数值。

```cpp
static constexpr int System::Convert::ToInt32(std::nullptr_t)
```

### 返回值

0。

## Convert::ToInt32(const char_t *) 方法

将包含数字字符串表示的 C 字符串转换为等效的 32 位整数值。

```cpp
static int System::Convert::ToInt32(const char_t *value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要转换的 C 字符串 |

### 返回值

等于指定 C 字符串所表示数字的 32 位整数值

## Convert::ToInt32(const String\&) 方法

将包含数字字符串表示的字符串转换为等效的 32 位整数值。

```cpp
static int System::Convert::ToInt32(const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |

### 返回值

等于指定字符串所表示数字的 32 位整数值

## Convert::ToInt32(const String\&, int) 方法

将指定基数下的数字字符串转换为等效的 32 位整数值。

```cpp
static int System::Convert::ToInt32(const String &value, int from_base)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| from_base | int | 字符串所表示数字的进制 |

### 返回值

等于指定字符串所表示数字的 32 位整数值

## Convert::ToInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息将包含数字字符串表示的字符串转换为等效的 32 位整数值。

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字符串格式信息的对象指针 |

### 返回值

等于指定字符串所表示数字的 32 位整数值

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, std::nullptr_t) 方法

```cpp
static int System::Convert::ToInt32(const String &value, std::nullptr_t)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息和数字样式将包含数字字符串表示的字符串转换为等效的 32 位整数值。

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 指定数字字符串表示允许样式的 NumberStyles 枚举值的按位组合 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字符串格式信息的对象指针 |

### 返回值

等于指定字符串所表示数字的 32 位整数值

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt32(Enum) 方法

```cpp
template<typename Enum,typename> static int32_t System::Convert::ToInt32(Enum value)
```

## Convert::ToInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

将指定的装箱值转换为等效的 32 位整数值。

```cpp
static int System::Convert::ToInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 装箱待转换值的对象的共享指针 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 当装箱值的类型为 [String](../../string/) 时使用的字符串格式 |

### 返回值

等效于指定装箱值的 32 位整数值

## 另请参阅

* 枚举 [NumberStyles](../../../system.globalization/numberstyles/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [Decimal](../../decimal/)
* 类 [DateTime](../../datetime/)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 类 [Object](../../object/)
* 结构体 [Convert](../)
* 结构体 [Enum](../../enum/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)