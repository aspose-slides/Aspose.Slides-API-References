---
title: Parse()
second_title: Aspose.Slides for C++ API 參考
description: 將字串轉換為等效的 TimeSpan 物件。
type: docs
weight: 534
url: /zh-hant/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) 方法

將字串轉換為等效的 [TimeSpan](../) 物件。

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Input string. |

### 返回值

與字串相對應的時間間隔。

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用指定的格式提供程序，將字串轉換為等效的 [TimeSpan](../) 物件。

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Input string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供文化特定格式資訊的格式提供程序。 |

### 返回值

與字串相對應的時間間隔。

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

## 另請參閱

* Typedef [SharedPtr](../../sharedptr/)
* 類別 [TimeSpan](../)
* 類別 [String](../../string/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)