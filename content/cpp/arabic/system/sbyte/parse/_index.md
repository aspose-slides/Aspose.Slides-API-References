---
title: Parse()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل رقمي لعدد إلى عدد صحيح موقع 8-بت مكافئ.
type: docs
weight: 1
url: /ar/system/sbyte/parse/
---
## SByte::Parse(const String\&) طريقة

تحول السلسلة المحددة التي تحتوي على تمثيل رقمي لعدد إلى عدد صحيح موقع 8-بت مكافئ.

```cpp
static int8_t System::SByte::Parse(const String &value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة للتحويل. |

### قيمة الإرجاع

عدد صحيح موقع 8-بت مكافئ للعدد الممثل في السلسلة المحددة.

## SByte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) طريقة

تحول السلسلة المحددة التي تحتوي على تمثيل رقمي لعدد إلى عدد صحيح موقع 8-بت مكافئ باستخدام معلومات التنسيق المقدمة.

```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة للتحويل. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### قيمة الإرجاع

عدد صحيح موقع 8-بت مكافئ للعدد الممثل في السلسلة المحددة.

## SByte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, std::nullptr_t) طريقة




```cpp
static int8_t System::SByte::Parse(const String &value, std::nullptr_t)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) طريقة

تحول السلسلة المحددة التي تحتوي على تمثيل رقمي لعدد إلى عدد صحيح موقع 8-بت مكافئ باستخدام معلومات التنسيق المقدمة ونمط الرقم.

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة للتحويل. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | تركيبة بتية من قيم تعداد NumberStyles تحدد النمط المسموح به لتمثيل السلسلة للعدد. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### قيمة الإرجاع

عدد صحيح موقع 8-بت مكافئ للعدد الممثل في السلسلة المحددة.

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) طريقة




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## انظر أيضًا

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)