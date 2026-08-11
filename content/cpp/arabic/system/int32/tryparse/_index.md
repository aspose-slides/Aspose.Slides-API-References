---
title: TryParse()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحول السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح موقع 32 بت مكافئ.
type: docs
weight: 14
url: /ar/system/int32/tryparse/
---
## Int32::TryParse(const String\&, int32_t\&) طريقة

يحوّل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح موقع 32 بت مكافئ.

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة التي سيتم تحويلها. |
| result | **int32_t**\& | المرجع إلى متغيّر عدد صحيح موقع 32 بت تُوضع فيه نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجحت عملية التحويل، وإلا - خطأ.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) طريقة

يحوّل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح موقع 32 بت مكافئ باستخدام معلومات التنسيق ونمط الرقم المزودة.

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة التي سيتم تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مجموعة بتية من قيم تعداد NumberStyles تُحدد النمط المسموح لتمثيل النص للعدد. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |
| result | **int32_t**\& | المرجع إلى متغيّر عدد صحيح موقع 32 بت تُوضع فيه نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجحت عملية التحويل، وإلا - خطأ.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) طريقة

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) طريقة

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) طريقة

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## انظر أيضًا

* التعداد [NumberStyles](../../../system.globalization/numberstyles/)
* نوع معرف [SharedPtr](../../sharedptr/)
* الفئة [String](../../string/)
* الفئة [Int32](../)
* الفئة [IFormatProvider](../../iformatprovider/)
* الفئة [CultureInfo](../../../system.globalization/cultureinfo/)
* الفئة [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* نطاق الأسماء [System](../../)
* المكتبة [Aspose.Slides](../../../)