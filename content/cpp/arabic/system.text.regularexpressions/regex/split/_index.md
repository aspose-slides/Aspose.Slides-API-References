---
title: Split()
second_title: مرجع API الخاص بـ Aspose.Slides للـ C++
description: يقسم السلسلة حسب تطابقات التعبير النمطي.
type: docs
weight: 105
url: /ar/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) طريقة

يقسم السلسلة حسب تطابقات التعبير النمطي.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) لتقسيمه. |

### قيمة الإرجاع

[Array](../../../system/array/) من السلاسل الفرعية بين التطابقات.

## Regex::Split(const String\&, int) طريقة

يقسم السلسلة حسب تطابقات التعبير النمطي.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) لتقسيمه. |
| count | int | عدد حدود السلاسل الفرعية. |

### قيمة الإرجاع

[Array](../../../system/array/) من السلاسل الفرعية بين التطابقات.

## Regex::Split(const String\&, int, int) طريقة

يقسم سلسلة الإدخال عددًا محددًا من المرات إلى مصفوفة من السلاسل الفرعية، في المواقع المحددة بواسطة تعبير نمطي مُحدد في مُنشئ [Regex](../). يبدأ البحث عن نمط التعبير النمطي عند موضع حرف محدد في سلسلة الإدخال.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | السلسلة التي سيتم تقسيمها. |
| count | int | الحد الأقصى لعدد مرات حدوث التقسيم. |
| startat | int | موضع الحرف في سلسلة الإدخال حيث سيبدأ البحث. |

### قيمة الإرجاع

مصفوفة من السلاسل.

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) طريقة

يقسم السلسلة وفقًا للتعبير النمطي.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | سلسلة الإدخال. |
| pattern | const [String](../../../system/string/)\& | نمط التعبير النمطي. |
| options | [RegexOptions](../../regexoptions/) | خيارات المطابقة. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | المهلة. |

### قيمة الإرجاع

[Array](../../../system/array/) من السلاسل بين التطابقات.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) طريقة

يقسم السلسلة وفقًا للتعبير النمطي.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | سلسلة الإدخال. |
| pattern | const [String](../../../system/string/)\& | نمط التعبير النمطي. |
| count | int | [Match](../../match/) عدد الحد. |
| options | [RegexOptions](../../regexoptions/) | خيارات المطابقة. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | المهلة. |

### قيمة الإرجاع

[Array](../../../system/array/) من السلاسل بين التطابقات.

## انظر أيضًا

* تعداد [RegexOptions](../../regexoptions/)
* تعريف_نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [Regex](../)
* فئة [TimeSpan](../../../system/timespan/)
* نطاق [System::Text::RegularExpressions](../../)
* مكتبة [Aspose.Slides](../../../)