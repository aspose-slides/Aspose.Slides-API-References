---
title: IsMatch()
second_title: Aspose.Slides برای C++ مرجع API
description: رشته را با عبارت منظم تطبیق می‌دهد.
type: docs
weight: 53
url: /fa/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) متد

Matches regex against string.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته هدف. |
| startat | int | شاخص شروع. |

### مقدار بازگشت

True اگر رشته با regex مطابقت داشته باشد، false در غیر این صورت.

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) متد

Checks if string matches pattern.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته ورودی. |
| pattern | const [String](../../../system/string/)\& | الگوی Regexp. |
| options | [RegexOptions](../../regexoptions/) | گزینه‌های مطابقت. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | محدودیت زمان. |
| startat | int | [Match](../../match/) موقعیت شروع. |

### مقدار بازگشت

True اگر تطابق یافت شد، false در غیر این صورت.

## موارد مرتبط

* Enum [RegexOptions](../../regexoptions/)
* کلاس [String](../../../system/string/)
* کلاس [Regex](../)
* کلاس [TimeSpan](../../../system/timespan/)
* فضای‌نام [System::Text::RegularExpressions](../../)
* کتابخانه [Aspose.Slides](../../../)