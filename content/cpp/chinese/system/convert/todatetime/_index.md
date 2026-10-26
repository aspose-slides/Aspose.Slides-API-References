---
title: ToDateTime()
second_title: Aspose.Slides C++ API 参考
description: 不支持转换。始终抛出 InvalidCastException.
type: docs
weight: 248
url: /zh/system/convert/todatetime/
---
## Convert::ToDateTime(bool) 方法


不支持转换。始终抛出 InvalidCastException。

```cpp
static DateTime System::Convert::ToDateTime(bool value)
```

## Convert::ToDateTime(uint8_t) 方法


不支持转换。始终抛出 InvalidCastException。

```cpp
static DateTime System::Convert::ToDateTime(uint8_t value)
```

## Convert::ToDateTime(int8_t) 方法


不支持转换。始终抛出 InvalidCastException。

```cpp
static DateTime System::Convert::ToDateTime(int8_t value)
```

## Convert::ToDateTime(uint16_t) 方法


不支持转换。始终抛出 InvalidCastException。

```cpp
static DateTime System::Convert::ToDateTime(uint16_t value)
```

## Convert::ToDateTime(int16_t) 方法


不支持转换。始终抛出 InvalidCastException。

```cpp
static DateTime System::Convert::ToDateTime(int16_t value)
```

## Convert::ToDateTime(uint32_t) 方法


不支持转换。始终抛出 InvalidCastException。

```cpp
static DateTime System::Convert::ToDateTime(uint32_t value)
```

## Convert::ToDateTime(int32_t) 方法


不支持转换。始终抛出 InvalidCastException。

```cpp
static DateTime System::Convert::ToDateTime(int32_t value)
```

## Convert::ToDateTime(uint64_t) 方法


不支持转换。始终抛出 InvalidCastException。

```cpp
static DateTime System::Convert::ToDateTime(uint64_t value)
```

## Convert::ToDateTime(int64_t) 方法


不支持转换。始终抛出 InvalidCastException。

```cpp
static DateTime System::Convert::ToDateTime(int64_t value)
```

## Convert::ToDateTime(float) 方法


不支持转换。始终抛出 InvalidCastException。

```cpp
static DateTime System::Convert::ToDateTime(float value)
```

## Convert::ToDateTime(double) 方法


不支持转换。始终抛出 InvalidCastException。

```cpp
static DateTime System::Convert::ToDateTime(double value)
```

## Convert::ToDateTime(const Decimal\&) 方法


不支持转换。始终抛出 InvalidCastException。

```cpp
static DateTime System::Convert::ToDateTime(const Decimal &value)
```

## Convert::ToDateTime(char_t) 方法


不支持转换。始终抛出 InvalidCastException。

```cpp
static DateTime System::Convert::ToDateTime(char_t value)
```

## Convert::ToDateTime(DateTime) 方法


返回指定的日期和时间。

```cpp
static constexpr DateTime System::Convert::ToDateTime(DateTime value)
```

## Convert::ToDateTime(const String\&) 方法


将指定的字符串转换为 [DateTime](../../datetime/) 类的实例。

```cpp
static DateTime System::Convert::ToDateTime(const String &value)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |

### 返回值

表示由指定字符串表示的日期和时间信息的 [DateTime](../../datetime/) 类实例

## Convert::ToDateTime(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法


使用提供的格式信息将指定的字符串转换为 [DateTime](../../datetime/) 类的实例。

```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<IFormatProvider> &fp)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字符串格式信息的对象指针 |

### 返回值

表示由指定字符串表示的日期和时间信息的 [DateTime](../../datetime/) 类实例

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) 方法




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## Convert::ToDateTime(const String\&, std::nullptr_t) 方法




```cpp
static DateTime System::Convert::ToDateTime(const String &value, std::nullptr_t)
```

## Convert::ToDateTime(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法


将指定的装箱值转换为等效的 [DateTime](../../datetime/) 值。

```cpp
static DateTime System::Convert::ToDateTime(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 装箱待转换值的对象的共享指针 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 如果装箱值的类型是 [String](../../string/)，则使用的字符串格式 |

### 返回值

等效于指定装箱值的 [DateTime](../../datetime/) 值

## 另见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [DateTime](../../datetime/)
* 类 [Decimal](../../decimal/)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 类 [Object](../../object/)
* 结构体 [Convert](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)