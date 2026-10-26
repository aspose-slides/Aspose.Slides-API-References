---
title: TryParse()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل العدد كسلسلة إلى عدد صحيح موقع 64-بت المكافئ.
type: docs
weight: 14
url: /ar/system/int64/tryparse/
---
## Int64::TryParse(const String\&, int64_t\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل العدد كسلسلة إلى عدد صحيح موقع 64-بت المكافئ.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```

### المعطيات

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| result | **int64_t**\& | المرجع إلى متغيّر عدد صحيح موقع 64-بت حيث يُوضع نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجحت العملية، وإلا - خطأ.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل العدد كسلسلة إلى عدد صحيح موقع 64-بت المكافئ باستخدام معلومات التنسيق والنمط المحددين.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```

### المعطيات

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مجموعة بتية من قيم تعداد NumberStyles التي تحدد النمط المسموح لتمثيل العدد كسلسلة. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |
| result | **int64_t**\& | المرجع إلى متغيّر عدد صحيح موقع 64-بت حيث يُوضع نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجحت العملية، وإلا - خطأ.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) طريقة

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) طريقة

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) طريقة

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## راجع أيضًا

* عدد [NumberStyles](../../../system.globalization/numberstyles/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [Int64](../)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)