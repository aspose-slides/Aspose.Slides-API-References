---
title: ToDateTimeOffset()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل السلسلة المزوَّدة إلى ما يعادلها من نوع DateTimeOffset.
type: docs
weight: 430
url: /ar/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) طريقة

يقوم بتحويل [String](../../../system/string/) المزوَّد إلى ما يعادله من نوع [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | السلسلة التي سيتم تحويلها. يجب أن تتوافق السلسلة مع أحد أجزاء توصية W3C لنوع XML dateTime. لمزيد من المعلومات، راجع القسم [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) من مواصفة XML [Schema](../../../system.xml.schema/). |

### قيمة الإرجاع

ما يعادل [DateTimeOffset](../../../system/datetimeoffset/) للسلسلة المزوَّدة.

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) طريقة

يقوم بتحويل [String](../../../system/string/) المزوَّد إلى ما يعادله من نوع [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | السلسلة التي سيتم تحويلها. |
| format | const [String](../../../system/string/)\& | الصيغة التي يتم تحويل **s** منها. يمكن أن يكون معامل الصيغة أي جزء من توصية W3C لنوع XML dateTime. لمزيد من المعلومات، راجع القسم [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) من مواصفة XML [Schema](../../../system.xml.schema/). يتم التحقق من صحة السلسلة **s** وفقًا لهذه الصيغة. |

### قيمة الإرجاع

ما يعادل [DateTimeOffset](../../../system/datetimeoffset/) للسلسلة المزوَّدة.

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) طريقة

يقوم بتحويل [String](../../../system/string/) المزوَّد إلى ما يعادله من نوع [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | السلسلة التي سيتم تحويلها. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | مصفوفة من الصيغ التي يمكن تحويل **s** منها. يمكن أن تكون كل صيغة في **formats** أي جزء من توصية W3C لنوع XML dateTime. لمزيد من المعلومات، راجع القسم [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) من مواصفة XML [Schema](../../../system.xml.schema/). يتم التحقق من صحة السلسلة **s** مقابل إحدى هذه الصيغ. |

### قيمة الإرجاع

ما يعادل [DateTimeOffset](../../../system/datetimeoffset/) للسلسلة المزوَّدة.

## أنظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* الفئة [DateTimeOffset](../../../system/datetimeoffset/)
* الفئة [String](../../../system/string/)
* الفئة [XmlConvert](../)
* الفضاء الاسمي [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)