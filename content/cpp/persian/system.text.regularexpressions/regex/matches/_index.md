---
title: Matches()
second_title: Aspose.Slides برای C++ مرجع API
description: تمام تطابق‌های regex را در رشتهٔ داده‌شده با تطبیق مکرر به‌دست می‌آورد.
type: docs
weight: 79
url: /fa/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) متد

تمام تطابق‌های regex را در رشتهٔ داده‌شده با تطبیق مکرر به‌دست می‌آورد.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشتهٔ ورودی. |
| startat | int | [Index](../../../system/index/) برای شروع تطبیق در. |

### مقدار بازگشتی

مجموعه‌ای از تمام تطابق‌های یافت‌شده.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) متد

تمام تطابق‌ها بین رشته و الگو را به‌دست می‌آورد.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشتهٔ ورودی. |
| pattern | const [String](../../../system/string/)\& | الگوی Regexp. |
| options | [RegexOptions](../../regexoptions/) | گزینه‌های تطبیق. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | مهلت. |
| startat | int | [Match](../../match/) موقعیت شروع. |
| length | int | تعداد کاراکترهایی که باید بررسی شود (0 محدودیت را غیرفعال می‌کند). |

### مقدار بازگشتی

تمام تطابق‌های یافت‌شده با تطبیق مکرر.

## موارد مرتبط

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* کلاس [String](../../../system/string/)
* کلاس [Regex](../)
* کلاس [TimeSpan](../../../system/timespan/)
* فضای‌نام [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)