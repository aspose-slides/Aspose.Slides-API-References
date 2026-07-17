---
title: Parse()
second_title: Aspose.Slides C++ API 参考
description: 将字符串转换为等价的 TimeSpan 对象。
type: docs
weight: 534
url: /zh/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) 方法

将字符串转换为等价的 [TimeSpan](../) 对象。

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 输入字符串。 |

### 返回值

与字符串对应的时间间隔。

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用指定的格式提供程序将字符串转换为等价的 [TimeSpan](../) 对象。

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 输入字符串。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供特定文化格式信息的格式提供程序。 |

### 返回值

与字符串对应的时间间隔。

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) 方法

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) 方法

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## 另请参阅

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [TimeSpan](../)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)