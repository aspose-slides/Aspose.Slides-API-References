---
title: Parse()
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++
description: يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح غير موقع 16-بت مكافئ.
type: docs
weight: 1
url: /ar/system/uint16/parse/
---
## UInt16::Parse(const String\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح غير موقع 16-بت مكافئ.

```cpp
static uint16_t System::UInt16::Parse(const String &value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |

### قيمة الإرجاع

عدد صحيح غير موقع 16-بت يساوي العدد الممثل بالسلسلة المحددة.

## UInt16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح غير موقع 16-بت مكافئ باستخدام معلومات التنسيق المقدمة.

```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### قيمة الإرجاع

عدد صحيح غير موقع 16-بت يساوي العدد الممثل بالسلسلة المحددة.

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة

```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة

```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, std::nullptr_t) طريقة

```cpp
static uint16_t System::UInt16::Parse(const String &value, std::nullptr_t)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح غير موقع 16-بت مكافئ باستخدام معلومات التنسيق المقدمة ونمط الرقم.

```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مزيج بتية من قيم تعداد NumberStyles التي تحدد النمط المسموح لتمثيل النص للعدد. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### قيمة الإرجاع

عدد صحيح غير موقع 16-بت يساوي العدد الممثل بالسلسلة المحددة.

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة

```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة

```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) طريقة

```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
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