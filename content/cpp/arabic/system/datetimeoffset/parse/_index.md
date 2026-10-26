---
title: Parse()
second_title: Aspose.Slides لمرجع API C++
description: يقوم بتحويل السلسلة المحددة إلى ما يعادل DateTimeOffset.
type: docs
weight: 703
url: /ar/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) طريقة

يقوم بتحويل السلسلة المحددة إلى ما يعادل [DateTimeOffset](../).

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) للتحويل. |

### قيمة الإرجاع

[DateTimeOffset](../) ما يعادل **input**.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) طريقة

يقوم بتحويل السلسلة المحددة إلى كائن [DateTimeOffset](../) باستخدام مزود التنسيق المحدد ونمط التنسيق المحدد.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) للتحويل. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مزود التنسيق. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | أنماط تنسيق التاريخ والوقت. |

### قيمة الإرجاع

[DateTimeOffset](../) ما يعادل **input**.

## انظر أيضًا

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)