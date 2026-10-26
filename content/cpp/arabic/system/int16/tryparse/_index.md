---
title: TryParse()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل عدد على شكل نص إلى عدد صحيح موقّع بحجم 16 بت مكافئ.
type: docs
weight: 14
url: /ar/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) method


يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل عدد على شكل نص إلى عدد صحيح موقّع بحجم 16 بت مكافئ.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| result | **int16_t**\& | المرجع إلى متغير عدد صحيح موقّع بحجم 16 بت حيث يتم وضع نتيجة التحويل. |

### القيمة المرجعة

True إذا نجحت عملية التحويل، وإلا - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) method


يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل عدد على شكل نص إلى عدد صحيح موقّع بحجم 16 بت مكافئ باستخدام معلومات التنسيق والنمط الرقمي المقدّمة.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مزيج بتّي من قيم تعداد NumberStyles يحدد النمط المسموح به لتمثيل العدد كسلسلة نصية. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |
| result | **int16_t**\& | المرجع إلى متغير عدد صحيح موقّع بحجم 16 بت حيث يتم وضع نتيجة التحويل. |

### القيمة المرجعة

True إذا نجحت عملية التحويل، وإلا - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## انظر أيضًا

* تعداد [NumberStyles](../../../system.globalization/numberstyles/)
* نوع معرف [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [Int16](../)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* فضاء الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)