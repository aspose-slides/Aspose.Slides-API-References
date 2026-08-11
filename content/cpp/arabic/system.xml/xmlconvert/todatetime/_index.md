---
title: ToDateTime()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بتحويل السلسلة إلى ما يعادل DateTime.
type: docs
weight: 417
url: /ar/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) طريقة

تحول [String](../../../system/string/) إلى ما يعادل [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | السلسلة المراد تحويلها. |

### قيمة الإرجاع

ما يعادل [DateTime](../../../system/datetime/) من السلسلة.

## XmlConvert::ToDateTime(const String\&, const String\&) طريقة

تحول [String](../../../system/string/) إلى ما يعادل [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | السلسلة المراد تحويلها. |
| format | const [String](../../../system/string/)\& | بنَية التنسيق لتطبيقها على [DateTime](../../../system/datetime/) المحول. تشمل الصيغ الصالحة "yyyy-MM-ddTHH:mm:sszzzzzz" ومشتقاتها. يتم التحقق من صحة السلسلة وفقًا لهذا التنسيق. |

### قيمة الإرجاع

ما يعادل [DateTime](../../../system/datetime/) من السلسلة.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) طريقة

تحول [String](../../../system/string/) إلى ما يعادل [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | السلسلة المراد تحويلها. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | مصفوفة تحتوي على بنى التنسيق لتطبيقها على [DateTime](../../../system/datetime/) المحول. تشمل الصيغ الصالحة "yyyy-MM-ddTHH:mm:sszzzzzz" ومشتقاتها. |

### قيمة الإرجاع

ما يعادل [DateTime](../../../system/datetime/) من السلسلة.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) طريقة

تحول [String](../../../system/string/) إلى ما يعادل [DateTime](../../../system/datetime/) باستخدام وضع XmlDateTimeSerializationMode المحدد.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | قيمة [String](../../../system/string/) للتحويل. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | إحدى قيم التعداد التي تحدد ما إذا كان يجب تحويل التاريخ إلى الوقت المحلي أو الحفاظ عليه كوقت عالمي منسق (UTC)، إذا كان التاريخ عبارة عن UTC. |

### قيمة الإرجاع

ما يعادل [DateTime](../../../system/datetime/) من [String](../../../system/string/).

## انظر أيضًا

* تعداد [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [DateTime](../../../system/datetime/)
* فئة [String](../../../system/string/)
* فئة [XmlConvert](../)
* فضاء الأسماء [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)