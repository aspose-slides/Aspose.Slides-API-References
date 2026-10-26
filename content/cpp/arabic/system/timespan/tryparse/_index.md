---
title: TryParse()
second_title: مرجع API Aspose.Slides لـ C++
description: يقوم بتحويل السلسلة إلى كائن TimeSpan مكافئ ويعيد نتيجة التحويل.
type: docs
weight: 560
url: /ar/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) طريقة

يقوم بتحويل السلسلة إلى كائن [TimeSpan](../) مكافئ ويعيد نتيجة التحويل.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | سلسلة الإدخال. |
| result | [TimeSpan](../)\& | الفترة الزمنية التي تتطابق مع السلسلة. |

### قيمة الإرجاع

صحيح إذا تم تحويل السلسلة بنجاح؛ وإلا، خاطئ.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) طريقة

يقوم بتحويل السلسلة إلى كائن [TimeSpan](../) مكافئ باستخدام مزود التنسيق المحدد ويعيد نتيجة التحويل.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | سلسلة الإدخال. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مزود التنسيق الذي يوفّر معلومات تنسيق مخصصة للثقافة. |
| result | [TimeSpan](../)\& | الفترة الزمنية التي تتطابق مع السلسلة. |

### قيمة الإرجاع

صحيح إذا تم تحويل السلسلة بنجاح؛ وإلا، خاطئ.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) طريقة

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) طريقة

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) طريقة

```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## انظر أيضا

* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [TimeSpan](../)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)