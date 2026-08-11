---
title: Replace()
second_title: مرجع API Aspose.Slides للغة C++
description: يستبدل جميع تطابقات regex في السلسلة بسلسلة الاستبدال.
type: docs
weight: 92
url: /ar/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) method


يستبدل جميع تطابقات regex في السلسلة بسلسلة الاستبدال.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | سلسلة الإدخال. |
| replacement | const [String](../../../system/string/)\& | سلسلة الاستبدال. |

### قيمة الإرجاع

سلسلة الإدخال مع استبدال جميع تطابقات regex بسلسلة الاستبدال.

## Regex::Replace(const String\&, const char_t *) method


يستبدل جميع تطابقات regex في السلسلة بسلسلة الاستبدال.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | سلسلة الإدخال. |
| replacement | const char_t * | سلسلة الاستبدال. |

### قيمة الإرجاع

سلسلة الإدخال مع استبدال جميع تطابقات regex بسلسلة الاستبدال.

## Regex::Replace(const String\&, const MatchEvaluator\&) method


يستبدل جميع التطابقات في السلسلة بسلاسل استبدال تم إنشاؤها بواسطة المفوض.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | سلسلة الإدخال. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | المفوض لإنشاء سلاسل الاستبدال بناءً على التطابقات. |

### قيمة الإرجاع

سلاسل الإدخال مع استبدال جميع التطابقات.

## Regex::Replace(const String\&, const MatchEvaluator\&, int) method


يستبدل جميع التطابقات في السلسلة بسلاسل استبدال تم إنشاؤها بواسطة المفوض.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | سلسلة الإدخال. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | المفوض لإنشاء سلاسل الاستبدال بناءً على التطابقات. |
| count | int | حد عدد الاستبدالات. |

### قيمة الإرجاع

سلاسل الإدخال مع استبدال جميع التطابقات.

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) method


يستبدل جميع التطابقات في السلسلة بسلاسل استبدال تم إنشاؤها بواسطة المفوض.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | سلسلة الإدخال. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | المفوض لإنشاء سلاسل الاستبدال بناءً على التطابقات. |
| count | int | حد عدد الاستبدالات. |
| startat | int | [Index](../../../system/index/) في سلسلة الإدخال لبدء الاستبدال عند. |

### قيمة الإرجاع

سلاسل الإدخال مع استبدال جميع التطابقات.

## Regex::Replace(const String\&, const String\&, int) method


يستبدل السلاسل الفرعية في السلسلة. غير مُنفّذ.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) method


يستبدل السلاسل الفرعية في السلسلة. غير مُنفّذ.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) method


يستبدل جميع تطابقات regex في السلسلة بسلسلة الاستبدال.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | سلسلة الإدخال. |
| pattern | const char_t * | [Regex](../) النمط. |
| replacement | const char_t * | سلسلة الاستبدال. |

### قيمة الإرجاع

سلسلة الإدخال مع استبدال جميع تطابقات regex بسلسلة الاستبدال.

## Regex::Replace(const String\&, const String\&, const char_t *) method


يستبدل جميع تطابقات regex في السلسلة بسلسلة الاستبدال.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | سلسلة الإدخال. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) النمط. |
| replacement | const char_t * | سلسلة الاستبدال. |

### قيمة الإرجاع

سلسلة الإدخال مع استبدال جميع تطابقات regex بسلسلة الاستبدال.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) method


يستبدل جميع التطابقات في السلسلة بسلاسل استبدال تم إنشاؤها بواسطة المفوض (دالة ثابتة).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | سلسلة الإدخال. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) النمط. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | المفوض لإنشاء سلاسل الاستبدال بناءً على التطابقات. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) الخيارات. |

### قيمة الإرجاع

سلاسل الإدخال مع استبدال جميع التطابقات.

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) method


يستبدل جميع تطابقات regex في السلسلة بسلسلة الاستبدال.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | سلسلة الإدخال. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) النمط. |
| replacement | const [String](../../../system/string/)\& | سلسلة الاستبدال. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) الخيارات. |

### قيمة الإرجاع

سلسلة الإدخال مع استبدال جميع تطابقات regex بسلسلة الاستبدال.

## Regex::Replace(const String\&, const String\&, const String\&) method


يستبدل تطابقات regex.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | سلسلة الإدخال. |
| pattern | const [String](../../../system/string/)\& | نمط Regexp. |
| replacement | const [String](../../../system/string/)\& | سلسلة الاستبدال. |

### قيمة الإرجاع

[String](../../../system/string/) مع استبدال جميع التطابقات.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) method


يستبدل تطابقات regex.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | سلسلة الإدخال. |
| pattern | const [String](../../../system/string/)\& | نمط Regexp. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | المفوض لإنشاء سلسلة الاستبدال لكل تطابق. |

### قيمة الإرجاع

[String](../../../system/string/) مع استبدال جميع التطابقات.

## انظر أيضًا

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)