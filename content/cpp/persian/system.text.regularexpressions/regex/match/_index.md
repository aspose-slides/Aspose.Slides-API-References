---
title: Match()
second_title: Aspose.Slides برای مرجع API C++
description: عبارت منظم را بر رشته تطبیق می‌دهد.
type: docs
weight: 66
url: /fa/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) متد

عبارت منظم را بر رشته تطبیق می‌دهد.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته هدف. |

### مقدار بازگشت

[Match](../../match/) مقدار شامل وضعیت تطبیق و زیرتطبیق‌ها.

## Regex::Match(const String\&, int, int) متد

عبارت منظم را بر رشته تطبیق می‌دهد.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته هدف. |
| startat | int | اندیس شروع. |
| length | int | تعداد کاراکترهایی که باید بررسی شوند (0 برای بررسی کل رشته). |

### مقدار بازگشت

[Match](../../match/) مقدار شامل وضعیت تطبیق و زیرتطبیق‌ها.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) متد

رشته و الگو را تطبیق می‌دهد.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته ورودی. |
| pattern | const [String](../../../system/string/)\& | الگوی Regexp. |
| options | [RegexOptions](../../regexoptions/) | گزینه‌های مطابقت. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | زمان‌سربری. |
| startat | int | [Match](../../match/) موقعیت شروع. |
| length | int | تعداد کاراکترهایی که باید بررسی شوند (0 محدودیت را غیرفعال می‌کند). |

### مقدار بازگشت

اولین تطبیق یافته.

## موارد مرتبط

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* کلاس [String](../../../system/string/)
* کلاس [Regex](../)
* کلاس [TimeSpan](../../../system/timespan/)
* فضای‌نام [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)