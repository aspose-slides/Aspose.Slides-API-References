---
title: Parse()
second_title: مرجع API Aspose.Slides للـ C++
description: يحول السلسلة إلى كائن TimeSpan مكافئ.
type: docs
weight: 534
url: /ar/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) طريقة


يحول السلسلة إلى كائن [TimeSpan](../) مكافئ.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```


### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | السلسلة المدخلة. |

### قيمة الإرجاع

الفاصل الزمني الذي يتطابق مع السلسلة.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) طريقة


يحول السلسلة إلى كائن [TimeSpan](../) مكافئ باستخدام موفر الصيغة المحدد.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```


### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | السلسلة المدخلة. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | موفر الصيغة الذي يزود معلومات تنسيق خاصة بالثقافة. |

### قيمة الإرجاع

الفاصل الزمني الذي يتطابق مع السلسلة.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) طريقة




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) طريقة




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## انظر أيضًا

* Typedef [SharedPtr](../../sharedptr/)
* فئة [TimeSpan](../)
* فئة [String](../../string/)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)