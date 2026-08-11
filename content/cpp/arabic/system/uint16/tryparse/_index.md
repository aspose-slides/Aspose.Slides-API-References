---
title: TryParse()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح غير موقّع ذو 16 بت مكافئ.
type: docs
weight: 14
url: /ar/system/uint16/tryparse/
---
## UInt16::TryParse(const String\&, uint16_t\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح غير موقّع ذو 16 بت مكافئ.

```cpp
static bool System::UInt16::TryParse(const String &value, uint16_t &result)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة التي سيتم تحويلها. |
| result | **uint16_t**\& | المرجع إلى متغيّر عدد صحيح غير موقّع ذو 16 بت حيث يُوضع نتيجة التحويل. |

### قيمة الإرجاع

True إذا نجحت عملية التحويل، وإلا - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint16_t\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح غير موقّع ذو 16 بت مكافئ باستخدام معلومات التنسيق والنمط الرقمي المقدّرة.

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint16_t &result)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة التي سيتم تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مجموعة قيم تعداد NumberStyles تمثل النمط المسموح به لتمثيل النص للعدد. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |
| result | **uint16_t**\& | المرجع إلى متغيّر عدد صحيح غير موقّع ذو 16 بت حيث يُوضع نتيجة التحويل. |

### قيمة الإرجاع

True إذا نجحت عملية التحويل، وإلا - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint16_t\&) طريقة

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint16_t\&) طريقة

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint16_t\&) طريقة

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint16_t &result)
```

## انظر أيضًا

* تعداد [NumberStyles](../../../system.globalization/numberstyles/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* بنية [UInt16](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)