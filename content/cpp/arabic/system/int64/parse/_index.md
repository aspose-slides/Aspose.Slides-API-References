---
title: Parse()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: تحول السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح موقّع 64-bit مكافئ.
type: docs
weight: 1
url: /ar/system/int64/parse/
---
## Int64::Parse(const String\&) طريقة

تحول السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح موقّع 64-bit مكافئ.

```cpp
static int64_t System::Int64::Parse(const String &value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة التي سيتم تحويلها. |

### قيمة الإرجاع

عدد صحيح موقّع 64-bit يساوي العدد الممثَّل بالسلسلة المحددة.

## Int64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) طريقة

تحول السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح موقّع 64-bit مكافئ باستخدام معلومات التنسيق المقدَّمة.

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة التي سيتم تحويلها. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### قيمة الإرجاع

عدد صحيح موقّع 64-bit يساوي العدد الممثَّل بالسلسلة المحددة.

## Int64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, std::nullptr_t) طريقة




```cpp
static int64_t System::Int64::Parse(const String &value, std::nullptr_t)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) طريقة

يحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح موقّع 64-bit مكافئ باستخدام معلومات التنسيق ونمط العدد المقدَّمة.

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة التي سيتم تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | تركيبة بتية من قيم تعداد NumberStyles الذي يحدّد نمط تمثيل السلسلة المسموح به. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### قيمة الإرجاع

عدد صحيح موقّع 64-bit يساوي العدد الممثَّل بالسلسلة المحددة.

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) طريقة




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## انظر أيضًا

* تعداد [NumberStyles](../../../system.globalization/numberstyles/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [Int64](../)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)