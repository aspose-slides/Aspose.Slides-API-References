---
title: ParseExact()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل تمثيل السلسلة المحدد لقيمة التاريخ والوقت إلى كائن DateTime المكافئ باستخدام التنسيق المحدد ومعلومات التنسيق الخاصة بالثقافة. يجب أن يتطابق تنسيق تمثيل السلسلة مع التنسيق المحدد تمامًا. يطرح استثناءً إذا فشل التحويل.
type: docs
weight: 872
url: /ar/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method

يقوم بتحويل تمثيل السلسلة المحدد لقيمة التاريخ والوقت إلى الكائن [DateTime](../) المكافئ باستخدام التنسيق المحدد ومعلومات التنسيق الخاصة بالثقافة. يجب أن يتطابق تنسيق تمثيل السلسلة مع التنسيق المحدد تمامًا. يطرح استثناءً إذا فشل التحويل.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../string/)\& | تمثيل السلسلة لقيمة التاريخ والوقت المراد تحويلها. |
| format | const [String](../../string/)\& | تنسيق السلسلة. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | الكائن [IFormatProvider](../../iformatprovider/) الذي يوفر معلومات التنسيق الخاصة بالثقافة. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | تركيبة بتية من قيم التعداد التي توفر معلومات إضافية حول **s**، حول عناصر النمط التي قد تكون موجودة في **s**، أو حول التحويل من **s** إلى كائن [DateTime](../). |

### قيمة الإرجاع

مثيل جديد من الفئة [DateTime](../) يمثل قيمة التاريخ والوقت المكافئة لتلك التي تم تمثيلها بالسلسلة المحددة.

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method

يقوم بتحويل تمثيل السلسلة المحدد لقيمة التاريخ والوقت إلى الكائن [DateTime](../) المكافئ باستخدام التنسيقات المحددة ومعلومات التنسيق الخاصة بالثقافة والنمط. يجب أن يتطابق تنسيق تمثيل السلسلة مع واحد أو أكثر من التنسيقات المحددة تمامًا. يطرح استثناءً إذا فشل التحويل.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../string/)\& | تمثيل السلسلة لقيمة التاريخ والوقت المراد تحويلها. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | مصفوفة تنسيقات السلسلة. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | الكائن [IFormatProvider](../../iformatprovider/) الذي يوفر معلومات التنسيق الخاصة بالثقافة. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | تركيبة بتية من قيم التعداد التي توفر معلومات إضافية حول **s**، حول عناصر النمط التي قد تكون موجودة في **s**، أو حول التحويل من **s** إلى كائن [DateTime](../). |

### قيمة الإرجاع

مثيل جديد من الفئة [DateTime](../) يمثل قيمة التاريخ والوقت المكافئة لتلك التي تم تمثيلها بالسلسلة المحددة.

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## انظر أيضًا

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)