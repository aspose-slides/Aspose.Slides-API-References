---
title: Parse()
second_title: Aspose.Slides للغة C++ – مرجع API
description: تحول السلسلة المحددة التي تحتوي على تمثيل النص للعدد إلى عدد صحيح غير موقع 32-بت مكافئ.
type: docs
weight: 1
url: /ar/system/uint32/parse/
---
## UInt32::Parse(const String\&) الطريقة

تحول السلسلة المحددة التي تحتوي على تمثيل النص للعدد إلى عدد صحيح غير موقع 32-بت مكافئ.

```cpp
static uint32_t System::UInt32::Parse(const String &value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |

### قيمة الإرجاع

عدد صحيح غير موقع 32-بت يساوي الرقم الممثَّل بالسلسلة المحددة.

## UInt32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) الطريقة

تحول السلسلة المحددة التي تحتوي على تمثيل النص للعدد إلى عدد صحيح غير موقع 32-بت مكافئ باستخدام معلومات التنسيق الموفَّرة.

```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### قيمة الإرجاع

عدد صحيح غير موقع 32-بت يساوي الرقم الممثَّل بالسلسلة المحددة.

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) الطريقة




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) الطريقة




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, std::nullptr_t) الطريقة




```cpp
static uint32_t System::UInt32::Parse(const String &value, std::nullptr_t)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) الطريقة

تحول السلسلة المحددة التي تحتوي على تمثيل النص للعدد إلى عدد صحيح غير موقع 32-بت مكافئ باستخدام معلومات التنسيق الموفَّرة ونمط العدد.

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | تركيبة بتية من قيم تعداد NumberStyles التي تحدد النمط المسموح به لتمثيل النص للعدد. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### قيمة الإرجاع

عدد صحيح غير موقع 32-بت يساوي الرقم الممثَّل بالسلسلة المحددة.

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) الطريقة




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) الطريقة




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) الطريقة




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## انظر أيضًا

* تعداد [NumberStyles](../../../system.globalization/numberstyles/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* هيكل [UInt32](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)