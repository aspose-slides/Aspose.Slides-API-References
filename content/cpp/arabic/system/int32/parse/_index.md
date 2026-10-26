---
title: Parse()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يحوِّل السلسلة المحددة التي تحتوي على تمثيل نصي للعدد إلى العدد الصحيح الموقَّع 32-بت المكافئ.
type: docs
weight: 1
url: /ar/system/int32/parse/
---
## Int32::Parse(const String\&) طريقة

يحوِّل السلسلة المحددة التي تحتوي على تمثيل سلسلة لعدد إلى العدد الصحيح الموقَّع 32 بت المكافئ.

```cpp
static int32_t System::Int32::Parse(const String &value)
```

### وسائط

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |

### القيمة المرجعة

العدد الصحيح الموقَّع 32 بت المكافئ للعدد الممثَّل بالسلسلة المحددة.

## Int32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) طريقة

يحوِّل السلسلة المحددة التي تحتوي على تمثيل سلسلة لعدد إلى العدد الصحيح الموقَّع 32 بت المكافئ باستخدام معلومات التنسيق المقدَّمة.

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### وسائط

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### القيمة المرجعة

العدد الصحيح الموقَّع 32 بت المكافئ للعدد الممثَّل بالسلسلة المحددة.

## Int32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة




```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, std::nullptr_t) طريقة




```cpp
static int32_t System::Int32::Parse(const String &value, std::nullptr_t)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) طريقة

يحوِّل السلسلة المحددة التي تحتوي على تمثيل سلسلة لعدد إلى العدد الصحيح الموقَّع 32 بت المكافئ باستخدام معلومات التنسيق المقدَّمة ونمط الرقم.

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### وسائط

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | توليفة بتية من قيم تعداد NumberStyles التي تحدد النمط المسموح لتمثيل السلسلة للعدد. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### القيمة المرجعة

العدد الصحيح الموقَّع 32 بت المكافئ للعدد الممثَّل بالسلسلة المحددة.

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) طريقة




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&) طريقة




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, std::nullptr_t) طريقة




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, std::nullptr_t)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) طريقة




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

## انظر أيضًا

* عدد [NumberStyles](../../../system.globalization/numberstyles/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [Int32](../)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* فئة [ReadOnlySpan](../../readonlyspan/)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)