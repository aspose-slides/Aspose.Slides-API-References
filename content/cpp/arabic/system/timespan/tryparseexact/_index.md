---
title: TryParseExact()
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++
description: يحول السلسلة إلى كائن TimeSpan مكافئ باستخدام الصيغ المحددة وموفر الصيغة، ويعيد نتيجة التحويل.
type: docs
weight: 573
url: /ar/system/timespan/tryparseexact/
---
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) طريقة

تحول السلسلة إلى كائن [TimeSpan](../) مكافئ باستخدام الصيغ المحددة وموفر الصيغة، وتُرجع نتيجة التحويل.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | سلسلة الإدخال. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) لسلاسل الصيغة. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | موفر الصيغة الذي يوفر معلومات التنسيق الخاصة بالثقافة. |
| result | [TimeSpan](../)\& | فترة زمنية تتطابق مع السلسلة. |

### قيمة الإرجاع

صحيح إذا تم تحويل السلسلة بنجاح؛ وإلا، خطأ.

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) طريقة




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) طريقة




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, TimeSpan\&) طريقة




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) طريقة

تحول السلسلة إلى كائن [TimeSpan](../) مكافئ باستخدام الصيغة المحددة وموفر الصيغة والأنماط، وتُرجع نتيجة التحويل.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | سلسلة الإدخال. |
| format | const [String](../../string/)\& | سلسلة صيغ قياسية أو مخصصة. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | موفر الصيغة الذي يوفر معلومات التنسيق الخاصة بالثقافة. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | يحدد العناصر التي قد تكون موجودة في سلسلة الإدخال. |
| result | [TimeSpan](../)\& | فترة زمنية تتطابق مع السلسلة. |

### قيمة الإرجاع

صحيح إذا تم تحويل السلسلة بنجاح؛ وإلا، خطأ.

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) طريقة




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) طريقة




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) طريقة




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) طريقة

تحول السلسلة إلى كائن [TimeSpan](../) مكافئ باستخدام الصيغ المحددة وموفر الصيغة والأنماط، وتُرجع نتيجة التحويل.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | سلسلة الإدخال. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) لسلاسل الصيغة. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | موفر الصيغة الذي يوفر معلومات التنسيق الخاصة بالثقافة. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | يحدد العناصر التي قد تكون موجودة في سلسلة الإدخال. |
| result | [TimeSpan](../)\& | فترة زمنية تتطابق مع السلسلة. |

### قيمة الإرجاع

صحيح إذا تم تحويل السلسلة بنجاح؛ وإلا، خطأ.

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) طريقة




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) طريقة




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) طريقة




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) طريقة

تحول السلسلة إلى كائن [TimeSpan](../) مكافئ باستخدام الصيغة المحددة وموفر الصيغة، وتُرجع نتيجة التحويل.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | سلسلة الإدخال. |
| format | const [String](../../string/)\& | سلسلة صيغ قياسية أو مخصصة. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | موفر الصيغة الذي يوفر معلومات التنسيق الخاصة بالثقافة. |
| result | [TimeSpan](../)\& | فترة زمنية تتطابق مع السلسلة. |

### قيمة الإرجاع

صحيح إذا تم تحويل السلسلة بنجاح؛ وإلا، خطأ.

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) طريقة




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) طريقة




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, TimeSpan\&) طريقة




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, TimeSpan &result)
```

## انظر أيضًا

* تعداد [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* تعريف نوع [ArrayPtr](../../arrayptr/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [TimeSpan](../)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* مساحة اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)