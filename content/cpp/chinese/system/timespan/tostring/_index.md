---
title: ToString()
second_title: Aspose.Slides C++ API 参考
description: 返回当前对象表示的时间间隔的字符串表示形式。
type: docs
weight: 261
url: /zh/system/timespan/tostring/
---
## TimeSpan::ToString() const 方法

返回当前对象表示的时间间隔的字符串表示形式。

```cpp
String System::TimeSpan::ToString() const
```

## TimeSpan::ToString(const String\&) const 方法

使用指定的格式，将当前对象的值转换为等效的字符串表示形式。

```cpp
String System::TimeSpan::ToString(const String &format) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const 方法

使用指定的格式和格式提供程序，将当前对象的值转换为等效的字符串表示形式。

```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const 方法




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const 方法




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## TimeSpan::ToString(const String\&, std::nullptr_t) const 方法




```cpp
String System::TimeSpan::ToString(const String &format, std::nullptr_t) const
```

## 另请参阅

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [TimeSpan](../)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)