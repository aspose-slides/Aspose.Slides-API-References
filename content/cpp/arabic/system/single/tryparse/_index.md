---
title: TryParse()
second_title: Aspose.Slides for C++ مرجع واجهة برمجة التطبيقات
description: يحول السلسلة المحددة التي تحتوي على تمثيل عدد إلى القيمة المكافئة ذات الفاصلة العائمة ذات الدقة الأحادية.
type: docs
weight: 14
url: /ar/system/single/tryparse/
---
## Single::TryParse(const String\&, float\&) طريقة

تحول السلسلة المحددة التي تحتوي على تمثيل عدد إلى القيمة المكافئة ذات الفاصلة العائمة ذات الدقة الأحادية.

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| result | **float**\& | المرجع إلى متغير عائم ذو دقة أحادية حيث تُوضَع نتيجة التحويل. |

### قيمة الإرجاع

True إذا نجحت عملية التحويل، وإلا - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, float\&) طريقة

تحول السلسلة المحددة التي تحتوي على تمثيل عدد إلى القيمة المكافئة ذات الفاصلة العائمة ذات الدقة الأحادية باستخدام معلومات التنسيق ونمط العدد المقدمين.

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مجموعة بتية من قيم تعداد NumberStyles التي تحدد النمط المسموح لتمثيل العدد كسلسلة. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |
| result | **float**\& | المرجع إلى متغير عائم ذو دقة أحادية حيث تُوضَع نتيجة التحويل. |

### قيمة الإرجاع

True إذا نجحت عملية التحويل، وإلا - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, float\&) طريقة




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, float\&) طريقة




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, float\&) طريقة




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## راجع أيضًا

* تعداد [NumberStyles](../../../system.globalization/numberstyles/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* بنية [Single](../)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)