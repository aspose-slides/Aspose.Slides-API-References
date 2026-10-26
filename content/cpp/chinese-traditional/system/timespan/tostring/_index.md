---
title: ToString()
second_title: Aspose.Slides C++ API 參考
description: 傳回目前物件所表示的時間間隔的字串表示形式。
type: docs
weight: 261
url: /zh-hant/system/timespan/tostring/
---
## TimeSpan::ToString() const 方法

傳回目前物件所表示的時間間隔的字串表示形式。

```cpp
String System::TimeSpan::ToString() const
```

## TimeSpan::ToString(const String\&) const 方法

使用指定的格式，將目前物件的值轉換為等效的字串表示形式。

```cpp
String System::TimeSpan::ToString(const String &format) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const 方法

使用指定的格式與格式提供程序，將目前物件的值轉換為等效的字串表示形式。

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

## 另請參閱

* Typedef [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [TimeSpan](../)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)