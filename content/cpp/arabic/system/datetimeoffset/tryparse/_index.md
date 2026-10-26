---
title: TryParse()
second_title: مرجع API Aspose.Slides للغة C++
description: يحاول تحويل السلسلة المحددة إلى كائن DateTimeOffset.
type: docs
weight: 729
url: /ar/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) طريقة


يحاول تحويل السلسلة المحددة إلى كائن [DateTimeOffset](../).

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```


### Arguments

| معامل | نوع | وصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) للتحويل. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) التي تعادل **input**. |

### قيمة الإرجاع

true إذا تم تحويل **input** بنجاح، وإلا - false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) طريقة


يحاول تحويل السلسلة المحددة إلى كائن [DateTimeOffset](../) باستخدام موفر الصيغة المحدد ونمط التنسيق.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Arguments

| معامل | نوع | وصف |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) للتحويل. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | موفر الصيغة. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | أنماط تنسيق التاريخ والوقت. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) التي تعادل **input**. |

### قيمة الإرجاع

true إذا تم تحويل **input** بنجاح، وإلا - false.

## أنظر أيضاً

* تعداد [DateTimeStyles](../../../system.globalization/datetimestyles/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [DateTimeOffset](../)
* فئة [IFormatProvider](../../iformatprovider/)
* مساحة اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)