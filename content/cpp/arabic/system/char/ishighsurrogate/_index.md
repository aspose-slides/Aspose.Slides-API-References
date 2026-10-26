---
title: IsHighSurrogate()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد ما إذا كان الحرف في الفهرس المحدد في السلسلة المحددة هو وحدة شفرة عالية UTF-16.
type: docs
weight: 40
url: /ar/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) method


يحدد ما إذا كان الحرف في الفهرس المحدد في السلسلة المحددة وحدة شفرة عالية (high surrogate) UTF-16.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../string/)\& | سلسلة |
| index | int | المؤشر في السلسلة المحددة للحرف المراد اختباره |

### قيمة الإرجاع

True إذا كان الحرف في الفهرس المحدد وحدة شفرة عالية UTF-16، وإلا - false

## Char::IsHighSurrogate(const char_t *, int) method


يحدد ما إذا كان الحرف في الفهرس المحدد في مخزن الأحرف المحدد هو وحدة عالية.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const char_t * | مؤشر إلى بداية مخزن الأحرف |
| idx | int | مؤشر يبدأ من الصفر في المخزن المحدد للحرف لاختباره |

### قيمة الإرجاع

True إذا كان الحرف في الفهرس المحدد وحدة عالية، وإلا - false

## Char::IsHighSurrogate(char_t) method


يحدد ما إذا كان الحرف المحدد هو وحدة عالية.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| c | char_t | الحرف لاختباره |

### قيمة الإرجاع

True إذا كان الحرف المحدد وحدة عالية، وإلا - false

## انظر أيضًا

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)