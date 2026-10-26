---
title: Matches()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحصل على جميع التطابقات للعبارة النمطية في السلسلة المعطاة عبر المطابقة المتكررة.
type: docs
weight: 79
url: /ar/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) طريقة

يسترجع جميع التطابقات للعبارة النمطية في السلسلة المحددة عبر المطابقة المتكررة.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | سلسلة الإدخال. |
| startat | int | [Index](../../../system/index/) لبدء المطابقة عند. |

### قيمة الإرجاع

مجموعة جميع التطابقات التي تم العثور عليها.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) طريقة

يسترجع جميع التطابقات بين السلسلة والنمط.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | سلسلة الإدخال. |
| pattern | const [String](../../../system/string/)\& | نمط التعبير النمطي. |
| options | [RegexOptions](../../regexoptions/) | خيارات المطابقة. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | مهلة. |
| startat | int | [Match](../../match/) موضع البداية. |
| length | int | عدد الأحرف التي يجب فحصها (0 يعطل الحد). |

### قيمة الإرجاع

جميع التطابقات التي تم العثور عليها عبر المطابقة المتكررة.

## انظر أيضاً

* تعداد [RegexOptions](../../regexoptions/)
* تعريف نوع [MatchCollectionPtr](../../matchcollectionptr/)
* فئة [String](../../../system/string/)
* فئة [Regex](../)
* فئة [TimeSpan](../../../system/timespan/)
* مساحة الاسم [System::Text::RegularExpressions](../../)
* مكتبة [Aspose.Slides](../../../)