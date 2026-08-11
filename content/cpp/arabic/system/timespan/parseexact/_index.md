---
title: ParseExact()
second_title: Aspose.Slides للغة C++ مرجع API
description: يحوّل السلسلة إلى كائن TimeSpan المكافئ باستخدام الصيغ المحددة ومزود الصيغة والأنماط.
type: docs
weight: 547
url: /ar/system/timespan/parseexact/
---
## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) طريقة

يحوّل السلسلة إلى كائن [TimeSpan](../) المكافئ باستخدام الصيغ المحددة ومزود الصيغة والأنماط.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | سلسلة الإدخال. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) لسلاسل الصيغ. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مزود الصيغة الذي يزود بمعلومات تنسيق مخصصة للثقافة. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | يحدد العناصر التي قد تكون موجودة في السلسلة المدخلة. |

### قيمة الإرجاع

الفاصل الزمني الذي يتطابق مع السلسلة.

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) طريقة

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) طريقة

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles) طريقة

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) طريقة

يحوّل السلسلة إلى كائن [TimeSpan](../) المكافئ باستخدام الصيغة المحددة ومزود الصيغة والأنماط.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | سلسلة الإدخال. |
| format | const [String](../../string/)\& | صيغة قياسية أو مخصصة. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مزود الصيغة الذي يزود بمعلومات تنسيق مخصصة للثقافة. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | يحدد العناصر التي قد تكون موجودة في السلسلة المدخلة. |

### قيمة الإرجاع

الفاصل الزمني الذي يتطابق مع السلسلة.

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) طريقة

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) طريقة

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles) طريقة

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## انظر أيضًا

* تعداد [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* تعريف نوع [ArrayPtr](../../arrayptr/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [TimeSpan](../)
* فئة [String](../../string/)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)