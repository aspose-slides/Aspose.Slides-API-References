---
title: ToString()
second_title: Aspose.Slides for C++ API 参考
description: 返回当前对象所表示的日期和时间值的字符串表示形式，使用当前区域性定义的格式约定。
type: docs
weight: 482
url: /zh/system/datetime/tostring/
---
## DateTime::ToString() const 方法


返回当前对象所表示的日期和时间值的字符串表示形式，使用当前区域性定义的格式约定。

```cpp
String System::DateTime::ToString() const
```


### 返回值

当前对象所表示的值的字符串表示形式

## DateTime::ToString(const String\&) const 方法


返回当前对象所表示的日期和时间值的字符串表示形式，使用指定的格式和当前区域性定义的格式约定。

```cpp
String System::DateTime::ToString(const String &format) const
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 格式字符串 |

### 返回值

当前对象所表示的值的字符串表示形式，按照 **format** 定义的格式以及当前区域性进行格式化。

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const 方法


返回当前对象所表示的日期和时间值的字符串表示形式，使用指定的格式信息。

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 表示格式信息的对象 |

### 返回值

当前对象所表示的值的字符串表示形式，按照 **formatProvider** 提供的格式信息进行格式化。

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const 方法




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const 方法




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const 方法




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const 方法


返回当前对象所表示的日期和时间值的字符串表示形式，使用指定的格式信息。

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 格式字符串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 表示格式信息的对象 |

### 返回值

当前对象所表示的值的字符串表示形式，按照 **provider** 提供的格式信息以及格式字符串 **format** 进行格式化。

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const 方法




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const 方法




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const 方法




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## 另请参阅

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [DateTime](../)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)