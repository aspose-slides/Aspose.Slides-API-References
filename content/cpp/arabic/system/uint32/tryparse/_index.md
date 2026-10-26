---
title: TryParse()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي للعدد إلى عدد صحيح غير موقع بحجم 32 بت مكافئ.
type: docs
weight: 14
url: /ar/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي للعدد إلى عدد صحيح غير موقع بحجم 32 بت مكافئ.

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```

### المعاملات

| معلمة | نوع | وصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| result | **uint32_t**\& | المرجع إلى متغيّر عدد صحيح غير موقع بحجم 32 بت حيث يتم وضع نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجحت عملية التحويل، وإلا - خطأ.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي للعدد إلى عدد صحيح غير موقع بحجم 32 بت مكافئ باستخدام معلومات التنسيق المقدَّة ونمط الرقم.

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```

### المعاملات

| معلمة | نوع | وصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مجموعة بتية من قيم تعداد NumberStyles التي تحدد النمط المسموح به لتمثيل النص للعدد. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |
| result | **uint32_t**\& | المرجع إلى متغيّر عدد صحيح غير موقع بحجم 32 بت حيث يتم وضع نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجحت عملية التحويل، وإلا - خطأ.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) طريقة




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) طريقة




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) طريقة




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## انظر أيضًا

* تعداد [NumberStyles](../../../system.globalization/numberstyles/)
* تعريف_نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* بنية [UInt32](../)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)