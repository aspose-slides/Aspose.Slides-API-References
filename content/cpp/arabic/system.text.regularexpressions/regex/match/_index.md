---
title: Match()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يطابق regex مع السلسلة.
type: docs
weight: 66
url: /ar/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) طريقة

يطابق regex مع السلسلة.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | السلسلة المستهدفة. |

### قيمة الإرجاع

[Match](../../match/) value containing match status and submatches.

## Regex::Match(const String\&, int, int) طريقة

يطابق regex مع السلسلة.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | السلسلة المستهدفة. |
| startat | int | فهرس البداية. |
| length | int | عدد الأحرف التي يجب فحصها (0 للفحص عبر السلسلة بأكملها). |

### قيمة الإرجاع

[Match](../../match/) value containing match status and submatches.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) طريقة

يطابق السلسلة والنمط.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | سلسلة الإدخال. |
| pattern | const [String](../../../system/string/)\& | نمط regexp. |
| options | [RegexOptions](../../regexoptions/) | خيارات المطابقة. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | مهلة. |
| startat | int | [Match](../../match/) موضع البداية. |
| length | int | عدد الأحرف التي يجب فحصها (0 يلغي الحد). |

### قيمة الإرجاع

العثور على أول مطابقة.

## انظر أيضًا

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)