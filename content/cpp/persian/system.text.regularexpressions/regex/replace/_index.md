---
title: Replace()
second_title: مرجع API Aspose.Slides برای C++
description: تمام تطابق‌های regex را در رشته با رشته جایگزین جایگزین می‌کند.
type: docs
weight: 92
url: /fa/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) متد

تمام مطابقت‌های regex را در رشته با رشته جایگزین می‌کند.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته ورودی. |
| replacement | const [String](../../../system/string/)\& | رشته جایگزین. |

### مقدار بازگشت

رشته ورودی با تمام مطابقت‌های regex که با رشته جایگزین جایگزین شده‌اند.

## Regex::Replace(const String\&, const char_t *) متد

تمام مطابقت‌های regex را در رشته با رشته جایگزین می‌کند.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته ورودی. |
| replacement | const char_t * | رشته جایگزین. |

### مقدار بازگشت

رشته ورودی با تمام مطابقت‌های regex که با رشته جایگزین جایگزین شده‌اند.

## Regex::Replace(const String\&, const MatchEvaluator\&) متد

تمام مطابقت‌ها را در رشته با رشته‌های جایگزین تولید شده توسط نماینده جایگزین می‌کند.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته ورودی. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | نماینده برای تولید رشته‌های جایگزین بر اساس مطابقت‌ها. |

### مقدار بازگشت

رشته‌های ورودی با تمام مطابقت‌ها جایگزین شده‌اند.

## Regex::Replace(const String\&, const MatchEvaluator\&, int) متد

تمام مطابقت‌ها را در رشته با رشته‌های جایگزین تولید شده توسط نماینده جایگزین می‌کند.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته ورودی. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | نماینده برای تولید رشته‌های جایگزین بر اساس مطابقت‌ها. |
| count | int | محدودیت تعداد جایگزینی. |

### مقدار بازگشت

رشته‌های ورودی با تمام مطابقت‌ها جایگزین شده‌اند.

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) متد

تمام مطابقت‌ها را در رشته با رشته‌های جایگزین تولید شده توسط نماینده جایگزین می‌کند.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته ورودی. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | نماینده برای تولید رشته‌های جایگزین بر اساس مطابقت‌ها. |
| count | int | محدودیت تعداد جایگزینی. |
| startat | int | [Index](../../../system/index/) در رشته ورودی برای شروع جایگزینی. |

### مقدار بازگشت

رشته‌های ورودی با تمام مطابقت‌ها جایگزین شده‌اند.

## Regex::Replace(const String\&, const String\&, int) متد

زیررشته‌ها را در رشته جایگزین می‌کند. اجرا نشده.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) متد

زیررشته‌ها را در رشته جایگزین می‌کند. اجرا نشده.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) متد

تمام مطابقت‌های regex را در رشته با رشته جایگزین می‌کند.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته ورودی. |
| pattern | const char_t * | [Regex](../) الگو. |
| replacement | const char_t * | رشته جایگزین. |

### مقدار بازگشت

رشته ورودی با تمام مطابقت‌های regex که با رشته جایگزین جایگزین شده‌اند.

## Regex::Replace(const String\&, const String\&, const char_t *) متد

تمام مطابقت‌های regex را در رشته با رشته جایگزین می‌کند.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته ورودی. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) الگو. |
| replacement | const char_t * | رشته جایگزین. |

### مقدار بازگشت

رشته ورودی با تمام مطابقت‌های regex که با رشته جایگزین جایگزین شده‌اند.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) متد

تمام مطابقت‌ها را در رشته با رشته‌های جایگزین تولید شده توسط نماینده (تابع ایستا) جایگزین می‌کند.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته ورودی. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) الگو. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | نماینده برای تولید رشته‌های جایگزین بر اساس مطابقت‌ها. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) گزینه‌ها. |

### مقدار بازگشت

رشته‌های ورودی با تمام مطابقت‌ها جایگزین شده‌اند.

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) متد

تمام مطابقت‌های regex را در رشته با رشته جایگزین می‌کند.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته ورودی. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) الگو. |
| replacement | const [String](../../../system/string/)\& | رشته جایگزین. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) گزینه‌ها. |

### مقدار بازگشت

رشته ورودی با تمام مطابقت‌های regex که با رشته جایگزین جایگزین شده‌اند.

## Regex::Replace(const String\&, const String\&, const String\&) متد

مطابقت‌های regex را جایگزین می‌کند.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته ورودی. |
| pattern | const [String](../../../system/string/)\& | الگوی Regexp. |
| replacement | const [String](../../../system/string/)\& | رشته جایگزین. |

### مقدار بازگشت

[String](../../../system/string/) با تمام مطابقت‌ها جایگزین شده است.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) متد

مطابقت‌های regex را جایگزین می‌کند.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | رشته ورودی. |
| pattern | const [String](../../../system/string/)\& | الگوی Regexp. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | نماینده برای تولید رشته جایگزین برای هر مطابقت. |

### مقدار بازگشت

[String](../../../system/string/) با تمام مطابقت‌ها جایگزین شده است.

## موارد مرتبط

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* کلاس [String](../../../system/string/)
* کلاس [Regex](../)
* فضای نام [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)