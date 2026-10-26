---
title: ParseExact()
second_title: Aspose.Slides لـ C++ مرجع واجهة برمجة التطبيقات
description: يقوم بتحويل السلسلة المحددة إلى كائن DateTimeOffset باستخدام التنسيق المحدد، ومزود التنسيق، وأسلوب التنسيق.
type: docs
weight: 716
url: /ar/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) طريقة

يقوم بتحويل السلسلة المحددة إلى كائن [DateTimeOffset](../) باستخدام التنسيق المحدد ومزود التنسيق وأسلوب التنسيق.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### المعلمات

| معمل | نوع | الوصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) للتحويل. |
| format | const [String](../../string/)\& | سلسلة التنسيق. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مقدم التنسيق. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | أنماط تنسيق التاريخ والوقت. |

### قيمة الإرجاع

[DateTimeOffset](../) المقابلة لـ **input**.

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) طريقة

يقوم بتحويل السلسلة المحددة إلى كائن [DateTimeOffset](../) باستخدام التنسيقات المحددة، ومزود التنسيق، وأسلو�� التنسيق.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### المعلمات

| معمل | نوع | الوصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) للتحويل. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) لسلاسل التنسيق. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مقدم التنسيق. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | أنماط تنسيق التاريخ والوقت. |

### قيمة الإرجاع

[DateTimeOffset](../) المقابلة لـ **input**.

## انظر أيضاً

* تعداد [DateTimeStyles](../../../system.globalization/datetimestyles/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* تعريف نوع [ArrayPtr](../../arrayptr/)
* فئة [DateTimeOffset](../)
* فئة [String](../../string/)
* فئة [IFormatProvider](../../iformatprovider/)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)