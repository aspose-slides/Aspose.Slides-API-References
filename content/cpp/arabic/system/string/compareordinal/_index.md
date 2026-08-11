---
title: CompareOrdinal()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقارن أقل-مساواة-أكبر سلسلتين باستخدام الوضع الترتيبي.
type: docs
weight: 833
url: /ar/system/string/compareordinal/
---
## String::CompareOrdinal(const String&, const String&) طريقة

يقارن السلسلتين بترتيب أقل-مساواة-أكبر باستخدام الوضع الترتيبي.

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| strB | const [String](../)\& | Second string to compare. |

### قيمة الإرجاع

قيمة سلبية إذا كان الجزء الفرعي الأول أصغر من الثاني، صفر إذا كانا متطابقتين، قيمة إيجابية غير ذلك.

## String::CompareOrdinal(const String&, int, const String&, int, int) طريقة

يقارن السلسلتين بترتيب أقل-مساواة-أكبر باستخدام الوضع الترتيبي.

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| indexA | int | Beginning of first string substring. |
| strB | const [String](../)\& | Second string to compare. |
| indexB | int | Beginning of the second string substring. |
| length | int | Number of characters to compare. |

### قيمة الإرجاع

قيمة سلبية إذا كان الجزء الفرعي الأول أصغر من الثاني، صفر إذا كانا متطابقتين، قيمة إيجابية غير ذلك.

## انظر أيضًا

* الفئة [String](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)