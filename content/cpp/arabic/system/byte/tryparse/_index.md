---
title: TryParse()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بتحويل السلسلة المحددة التي تحتوي على التمثيل النصي لعدد إلى عدد صحيح غير موقع بحجم 8-bit مكافئ.
type: docs
weight: 14
url: /ar/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) طريقة


تحول السلسلة المحددة التي تحتوي على التمثيل النصي لعدد إلى عدد صحيح غير موقع 8-بت مكافئ.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```


### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| result | **uint8_t**\& | المرجع إلى متغير عدد صحيح غير موقع 8-بت حيث يتم وضع نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجح التحويل، وإلا - خطأ.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) طريقة


تحول السلسلة المحددة التي تحتوي على التمثيل النصي لعدد إلى عدد صحيح غير موقع 8-بت مكافئ باستخدام معلومات التنسيق ونمط العدد المقدمة.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```


### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مزيج بتّي من قيم تعداد NumberStyles يحدد النمط المسموح به للتمثيل النصي للعدد. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |
| result | **uint8_t**\& | المرجع إلى متغير عدد صحيح غير موقع 8-بت حيث يتم وضع نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجح التحويل، وإلا - خطأ.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) طريقة




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) طريقة




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) طريقة




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## انظر أيضًا

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Byte](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)