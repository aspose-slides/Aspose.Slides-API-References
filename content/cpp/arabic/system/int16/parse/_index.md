---
title: Parse()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل عدد على هيئة سلسلة إلى عدد صحيح موقع 16-بت مكافئ.
type: docs
weight: 1
url: /ar/system/int16/parse/
---
## Int16::Parse(const String\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل عدد على هيئة سلسلة إلى عدد صحيح موقع 16-بت مكافئ.

```cpp
static int16_t System::Int16::Parse(const String &value)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |

### قيمة الإرجاع

العدد الصحيح الموقع 16-بت المكافئ للعدد الممثل في السلسلة المحددة.

## Int16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل عدد على هيئة سلسلة إلى عدد صحيح موقع 16-بت مكافئ باستخدام معلومات التنسيق المقدمة.

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### قيمة الإرجاع

العدد الصحيح الموقع 16-بت المكافئ للعدد الممثل في السلسلة المحددة.

## Int16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, std::nullptr_t) طريقة




```cpp
static int16_t System::Int16::Parse(const String &value, std::nullptr_t)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل عدد على هيئة سلسلة إلى عدد صحيح موقع 16-بت مكافئ باستخدام معلومات التنسيق المقدمة ونمط الرقم.

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مجموعة تجميعية بتية لقيم تعداد NumberStyles التي تحدد النمط المسموح به لتمثيل عدد على هيئة سلسلة. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### قيمة الإرجاع

العدد الصحيح الموقع 16-بت المكافئ للعدد الممثل في السلسلة المحددة.

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) طريقة




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## انظر أيضًا

* تعداد [NumberStyles](../../../system.globalization/numberstyles/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [Int16](../)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* مساحة اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)