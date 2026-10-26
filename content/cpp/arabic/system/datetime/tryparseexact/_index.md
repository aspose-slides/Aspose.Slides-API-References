---
title: TryParseExact()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بتحويل تمثيل السلسلة المحدد لقيمة تاريخ ووقت إلى كائن DateTime المعادل باستخدام الصيغة المحددة ومعلومات التنسيق الخاصة بالثقافة والنمط. يجب أن يتطابق تمثيل السلسلة مع الصيغة المحددة تمامًا.
type: docs
weight: 898
url: /ar/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) طريقة

يقوم بتحويل تمثيل السلسلة المحدد لقيمة تاريخ ووقت إلى الكائن [DateTime](../) المعادل باستخدام الصيغة المحددة ومعلومات التنسيق الخاصة بالثقافة والنمط. يجب أن يتطابق تمثيل السلسلة مع الصيغة المحددة تمامًا.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../string/)\& | تمثيل السلسلة لقيمة تاريخ ووقت للتحويل. |
| format | const [String](../../string/)\& | صيغة السلسلة. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | كائن [IFormatProvider](../../iformatprovider/) الذي يوفر معلومات تنسيق خاصة بالثقافة. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | مجموعة بتية من قيم التعداد التي توفر معلومات إضافية حول **s**، حول عناصر النمط التي قد تكون موجودة في **s**، أو حول التحويل من **s** إلى كائن [DateTime](../). |
| result | [DateTime](../)\& | معامل الإخراج الذي، إذا نجحت عملية التحويل، يحتوي على نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجحت عملية التحويل، وإلا - خطأ.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) طريقة

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) طريقة

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) طريقة

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) طريقة

يقوم بتحويل تمثيل السلسلة المحدد لقيمة تاريخ ووقت إلى الكائن [DateTime](../) المعادل باستخدام الصيغ المحددة ومعلومات التنسيق الخاصة بالثقافة والنمط. يجب أن يتطابق تمثيل السلسلة مع صيغة واحدة أو أكثر من الصيغ المحددة تمامًا.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../string/)\& | تمثيل السلسلة لقيمة تاريخ ووقت للتحويل. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | مصفوفة صيغ السلاسل. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | كائن [IFormatProvider](../../iformatprovider/) الذي يوفر معلومات تنسيق خاصة بالثقافة. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | مجموعة بتية من قيم التعداد التي توفر معلومات إضافية حول **s**، حول عناصر النمط التي قد تكون موجودة في **s**، أو حول التحويل من **s** إلى كائن [DateTime](../). |
| result | [DateTime](../)\& | معامل الإخراج الذي، إذا نجحت عملية التحويل، يحتوي على نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجحت عملية التحويل، وإلا - خطأ.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) طريقة

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) طريقة

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) طريقة

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## أنظر أيضًا

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* فئة [String](../../string/)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [DateTime](../)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* مساحة الاسم [System](../../)
* Library [Aspose.Slides](../../../)