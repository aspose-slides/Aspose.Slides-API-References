---
title: Parse()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل تمثيل النص المحدد لقيمة تاريخ ووقت إلى الكائن DateTime المعادل.
type: docs
weight: 859
url: /ar/system/datetime/parse/
---
## DateTime::Parse(const String\&) طريقة

يقوم بتحويل تمثيل النص المحدد لقيمة تاريخ ووقت إلى الكائن [DateTime](../) المعادل.

```cpp
static DateTime System::DateTime::Parse(const String &s)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../string/)\& | تمثيل النص لقيمة تاريخ ووقت للتحويل. |

### قيمة الإرجاع

نسخة جديدة من الفئة [DateTime](../) تمثل قيمة التاريخ والوقت المعادلة لتلك التي يمثلها النص المحدد.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) طريقة

يقوم بتحويل تمثيل النص المحدد لقيمة تاريخ ووقت إلى الكائن [DateTime](../) المعادل باستخدام معلومات تنسيق خاصة بالثقافة.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../string/)\& | تمثيل النص لقيمة تاريخ ووقت للتحويل. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | الكائن [IFormatProvider](../../iformatprovider/) الذي يوفر معلومات تنسيق خاصة بالثقافة. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | مجموعة بتية من قيم التعداد التي توفر معلومات إضافية حول **s**، حول عناصر النمط التي قد تكون موجودة في **s**، أو حول التحويل من **s** إلى كائن [DateTime](../). |

### قيمة الإرجاع

نسخة جديدة من الفئة [DateTime](../) تمثل قيمة التاريخ والوقت المعادلة لتلك التي يمثلها النص المحدد.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) طريقة

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) طريقة

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) طريقة

```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## انظر أيضا

* تعداد [DateTimeStyles](../../../system.globalization/datetimestyles/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [DateTime](../)
* فئة [String](../../string/)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* نطاق اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)