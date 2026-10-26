---
title: Parse()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحوّل السلسلة المحددة التي تحتوي على تمثيل العدد كنص إلى عدد صحيح غير موقع 64-بت مكافئ.
type: docs
weight: 1
url: /ar/system/uint64/parse/
---
## UInt64::Parse(const String\&) طريقة


يحوّل السلسلة المحددة التي تحتوي على تمثيل عدد على شكل نص إلى عدد صحيح غير موقع 64-بت مكافئ.

```cpp
static uint64_t System::UInt64::Parse(const String &value)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |

### قيمة الإرجاع

العدد الصحيح غير الموقع 64-بت المتساوي للعدد الممثَّل بالسلسلة المحددة.

## UInt64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) طريقة


يحوّل السلسلة المحددة التي تحتوي على تمثيل عدد على شكل نص إلى عدد صحيح غير موقع 64-بت مكافئ باستخدام معلومات التنسيق المقدمة.

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | إشارة إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### قيمة الإرجاع

العدد الصحيح غير الموقع 64-بت المتساوي للعدد الممثَّل بالسلسلة المحددة.

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, std::nullptr_t) طريقة




```cpp
static uint64_t System::UInt64::Parse(const String &value, std::nullptr_t)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) طريقة


يحوّل السلسلة المحددة التي تحتوي على تمثيل عدد على شكل نص إلى عدد صحيح غير موقع 64-بت مكافئ باستخدام معلومات التنسيق المقدمة ونمط العدد.

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | تركيبة بتية لقيم NumberStyles enum تحدد النمط المسموح به لتمثيل النص للعدد. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | إشارة إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### قيمة الإرجاع

العدد الصحيح غير الموقع 64-بت المتساوي للعدد الممثَّل بالسلسلة المحددة.

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) طريقة




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## انظر أيضًا

* تعداد [NumberStyles](../../../system.globalization/numberstyles/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* هيكل [UInt64](../)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)