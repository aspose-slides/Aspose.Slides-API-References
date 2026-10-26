---
title: TryParse()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بتحويل السلسلة المحددة التي تحتوي على التمثيل النصي لعدد إلى العدد الصحيح الموقّع ذو 8 بت المكافئ.
type: docs
weight: 14
url: /ar/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) طريقة


يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح موقّع 8-بِت مكافئ.

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```


### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| result | **int8_t**\& | المرجع إلى متغيّر عدد صحيح موقّع 8-بِت تُوضَع فيه نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجحت عملية التحويل، وإلا - خطأ.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) طريقة


يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح موقّع 8-بِت مكافئ باستخدام معلومات التنسيق ونمط الرقم المقدَّمين.

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```


### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مجموعة بتية من قيم تعداد NumberStyles تُحدِّد النمط المسموح به لتمثيل النص للعدد. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |
| result | **int8_t**\& | المرجع إلى متغيّر عدد صحيح موقّع 8-بِت تُوضَع فيه نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجحت عملية التحويل، وإلا - خطأ.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int8_t\&) طريقة




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int8_t\&) طريقة




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int8_t\&) طريقة




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int8_t &result)
```

## انظر أيضا

* تعداد [NumberStyles](../../../system.globalization/numberstyles/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* بنية [SByte](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)