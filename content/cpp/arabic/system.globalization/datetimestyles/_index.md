---
title: DateTimeStyles
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يعرف خيارات تنسيق التاريخ والوقت. أعلام البت.
type: docs
weight: 456
url: /ar/system.globalization/datetimestyles/
---
## DateTimeStyles enum

يحدد خيارات تنسيق التاريخ والوقت. أعلام البت.

```cpp
enum class DateTimeStyles : int32_t
```

### Values

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | 0 | الافتراضي. |
| AllowLeadingWhite | 1 | تجاهل المسافات البيضاء الأولية. |
| AllowTrailingWhite | 2 | تجاهل المسافات البيضاء اللاحقة. |
| AllowInnerWhite | 4 | تجاهل المسافات البيضاء الداخلية. |
| AllowWhiteSpaces | n/a | تجاهل جميع المسافات البيضاء. |
| NoCurrentDateDefault | 8 | عند تحليل سلسلة تاريخ/وقت، إذا كانت جميع مكونات السنة/الشهر/اليوم مفقودة، يتم تعيين التاريخ الافتراضي إلى 0001/1/1 بدلاً من السنة/الشهر/اليوم الحاليين. |
| AdjustToUniversal | 16 | عند تحليل سلسلة تاريخ/وقت، إذا كان هناك محدد منطقة زمنية ("GMT","Z","+xxxx","-xxxx")، سنقوم بضبط الوقت المُحلل بناءً على توقيت غرينتش. |
| AssumeLocal | 32 | إذا لم يتم تحديد منطقة زمنية، استخدم المنطقة الزمنية المحلية. |
| AssumeUniversal | 64 | إذا لم يتم تحديد منطقة زمنية، استخدم توقيت UTC. |
| RoundtripKind | 128 | محاولة الحفاظ على ما إذا كان الإدخال غير محدد أو محلي أو UTC. |

## انظر أيضًا

* نطاق [System::Globalization](../)
* المكتبة [Aspose.Slides](../../)