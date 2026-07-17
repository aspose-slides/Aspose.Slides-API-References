---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 将字符串转换为等价的 TimeSpan 对象并返回转换结果。
type: docs
weight: 560
url: /zh/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) 方法

将字符串转换为等价的 [TimeSpan](../) 对象并返回转换结果。

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 输入字符串。 |
| result | [TimeSpan](../)\& | 与字符串对应的时间间隔。 |

### 返回值

如果字符串成功转换则返回 true；否则返回 false。

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) 方法

使用指定的格式提供程序将字符串转换为等价的 [TimeSpan](../) 对象并返回转换结果。

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 输入字符串。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供特定文化格式信息的格式提供程序。 |
| result | [TimeSpan](../)\& | 与字符串对应的时间间隔。 |

### 返回值

如果字符串成功转换则返回 true；否则返回 false。

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) 方法

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) 方法

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) 方法

```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## 另请参见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [TimeSpan](../)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)