---
title: TryParseExact()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحاول تحويل السلسلة المحددة إلى كائن DateTimeOffset باستخدام الصيغ المحددة، ومزود الصيغة، ونمط التنسيق.
type: docs
weight: 742
url: /ar/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) طريقة

يحاول تحويل السلسلة المحددة إلى كائن [DateTimeOffset](../) باستخدام الصيغ المحددة ومزود الصيغ ونمط التنسيق.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) للتحويل. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | مصفوفات من سلاسل الصيغة. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مزود الصيغة. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | أنماط تنسيق التاريخ والوقت. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) التي تعادل **input**. |

### القيمة المرجعة

true إذا تم تحويل **input** بنجاح، وإلا false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) طريقة

يحاول تحويل السلسلة المحددة إلى كائن [DateTimeOffset](../) باستخدام الصيغة المحددة ومزود الصيغ ونمط التنسيق.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) للتحويل. |
| format | const [String](../../string/)\& | سلسلة الصيغة. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مزود الصيغة. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | أنماط تنسيق التاريخ والوقت. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) التي تعادل **input**. |

### القيمة المرجعة

true إذا تم تحويل **input** بنجاح، وإلا false.

## انظر أيضًا

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)