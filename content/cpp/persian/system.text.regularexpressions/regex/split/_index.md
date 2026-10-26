---
title: Split()
second_title: مرجع API Aspose.Slides برای C++
description: رشته را با تطابق‌های regex تقسیم می‌کند.
type: docs
weight: 105
url: /fa/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) متد

رشته را با تطابق‌های regex تقسیم می‌کند.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) برای تقسیم. |

### مقدار بازگشت

[Array](../../../system/array/) از زیررشته‌های بین تطابق‌ها.

## Regex::Split(const String\&, int) متد

رشته را با تطابق‌های regex تقسیم می‌کند.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) برای تقسیم. |
| count | int | حداکثر تعداد زیررشته‌ها. |

### مقدار بازگشت

[Array](../../../system/array/) از زیررشته‌های بین تطابق‌ها.

## Regex::Split(const String\&, int, int) متد

رشته ورودی را تا حداکثر تعداد مشخص شده بار به آرایه‌ای از زیررشته‌ها تقسیم می‌کند، در موقعیت‌هایی که توسط یک عبارت منظم تعریف شده در سازنده [Regex](../) مشخص می‌شود. جستجو برای الگوی عبارت منظم از موقعیت کاراکتری مشخصی در رشته ورودی آغاز می‌شود.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته‌ای که باید تقسیم شود. |
| count | int | حداکثر تعداد دفعاتی که تقسیم می‌تواند رخ دهد. |
| startat | int | موقعیت کاراکتر در رشته ورودی که جستجو از آنجا آغاز می‌شود. |

### مقدار بازگشت

یک آرایه از رشته‌ها.

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) متد

رشته را با regexp تقسیم می‌کند.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته ورودی. |
| pattern | const [String](../../../system/string/)\& | الگوی regexp. |
| options | [RegexOptions](../../regexoptions/) | گزینه‌های مطابقت. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | زمان‌سنجی. |

### مقدار بازگشت

[Array](../../../system/array/) از رشته‌های بین تطابق‌ها.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) متد

رشته را با regexp تقسیم می‌کند.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته ورودی. |
| pattern | const [String](../../../system/string/)\& | الگوی regexp. |
| count | int | [Match](../../match/) محدودیت عددی. |
| options | [RegexOptions](../../regexoptions/) | گزینه‌های مطابقت. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | زمان‌سنجی. |

### مقدار بازگشت

[Array](../../../system/array/) از رشته‌های بین تطابق‌ها.

## موارد مرتبط

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)