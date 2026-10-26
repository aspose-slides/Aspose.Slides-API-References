---
title: IsSortable()
second_title: مرجع API Aspose.Slides للغة C++
description: يفحص ما إذا كان الحرف المحدد قابلًا للترتيب.
type: docs
weight: 196
url: /ar/system.globalization/compareinfo/issortable/
---
## CompareInfo::IsSortable(char16_t) طريقة


يفحص ما إذا كان الحرف المحدد قابلًا للترتيب.

```cpp
static bool System::Globalization::CompareInfo::IsSortable(char16_t ch)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ch | char16_t | حرف يونيكود. |

### قيمة الإرجاع

صحيح إذا كان **ch** قابلًا للترتيب؛ وإلا خطأ.

## CompareInfo::IsSortable(const String\&) طريقة


يفحص ما إذا كان النص المحدد قابلًا للترتيب.

```cpp
static bool System::Globalization::CompareInfo::IsSortable(const String &text)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | نص. |

### قيمة الإرجاع

صحيح إذا لم يكن **text** فارغًا وجميع الأحرف في **text** قابلة للترتيب؛ وإلا خطأ.

## انظر أيضًا

* الفئة [CompareInfo](../)
* الفئة [String](../../../system/string/)
* النطاق [System::Globalization](../../)
* المكتبة [Aspose.Slides](../../../)