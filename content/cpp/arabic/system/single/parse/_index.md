---
title: Parse()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عائمة ذات دقة أحادية مكافئة.
type: docs
weight: 1
url: /ar/system/single/parse/
---
## Single::Parse(const String\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عائمة ذات دقة أحادية مكافئة.

```cpp
static float System::Single::Parse(const String &value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة التي سيتم تحويلها. |

### قيمة الإرجاع

قيمة عائمة ذات دقة أحادية مكافئة للعدد الممثل بالسلسلة المحددة.

## Single::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عائمة ذات دقة أحادية مكافئة باستخدام معلومات التنسيق المقدمة.

```cpp
static float System::Single::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة التي سيتم تحويلها. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### قيمة الإرجاع

قيمة عائمة ذات دقة أحادية مكافئة للعدد الممثل بالسلسلة المحددة.

## Single::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, std::nullptr_t) طريقة




```cpp
static float System::Single::Parse(const String &value, std::nullptr_t)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عائمة ذات دقة أحادية مكافئة باستخدام معلومات التنسيق المقدمة ونمط الرقم.

```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة التي سيتم تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | تركيبة بتية من قيم تعداد NumberStyles التي تحدد النمط المسموح به للتمثيل النصي للعدد. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### قيمة الإرجاع

قيمة عائمة ذات دقة أحادية مكافئة للعدد الممثل بالسلسلة المحددة.

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) طريقة




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## انظر أيضًا

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)