---
title: IsMatch()
second_title: Aspose.Slides لـ C++ مرجع واجهة برمجة التطبيقات
description: يطابق regex مع النص.
type: docs
weight: 53
url: /ar/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) طريقة

يطابق regex مع النص.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | السلسلة المستهدفة. |
| startat | int | فهرس البداية. |

### قيمة الإرجاع

true إذا كان النص يطابق regex، false خلاف ذلك.

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) طريقة

يتحقق مما إذا كان النص يطابق النمط.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | سلسلة الإدخال. |
| pattern | const [String](../../../system/string/)\& | نمط التعبير النمطي. |
| options | [RegexOptions](../../regexoptions/) | خيارات المطابقة. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | مهلة. |
| startat | int | [Match](../../match/) موضع البداية. |

### قيمة الإرجاع

true إذا وُجد تطابق، false خلاف ذلك.

## انظر أيضًا

* Enum [RegexOptions](../../regexoptions/)
* فئة [String](../../../system/string/)
* فئة [Regex](../)
* فئة [TimeSpan](../../../system/timespan/)
* مساحة الاسم [System::Text::RegularExpressions](../../)
* مكتبة [Aspose.Slides](../../../)