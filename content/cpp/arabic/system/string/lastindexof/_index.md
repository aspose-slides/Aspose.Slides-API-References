---
title: LastIndexOf()
second_title: مرجع API Aspose.Slides للغة C++
description: بحث خلفي عن سلسلة فرعية.
type: docs
weight: 651
url: /ar/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const طريقة

البحث الخلفي عن سلسلة فرعية.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../)\& | السلسلة الفرعية للبحث عنها. |
| startIndex | int | الموضع في السلسلة المصدر للبدء بالبحث من خلاله. |

### قيمة الإرجاع

[Index](../../index/) لأخر سلسلة فرعية تم العثور عليها أو -1 إذا لم يتم العثور عليها. بالنسبة لسلسلة بحث فارغة، تُرجع دائمًا طول السلسلة.

## String::LastIndexOf(const String\&, System::StringComparison) const طريقة

البحث الخلفي عن سلسلة فرعية.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../)\& | السلسلة الفرعية للبحث عنها. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | وضع [Comparison](../../comparison/). |

### قيمة الإرجاع

[Index](../../index/) لأخر سلسلة فرعية تم العثور عليها أو -1 إذا لم يتم العثور عليها. بالنسبة لسلسلة بحث فارغة، تُرجع دائمًا طول السلسلة.

## String::LastIndexOf(const String\&, int, System::StringComparison) const طريقة

البحث الخلفي عن سلسلة فرعية.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../)\& | السلسلة الفرعية للبحث عنها. |
| startIndex | int | الموضع في السلسلة المصدر للبدء بالبحث من خلاله. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | وضع [Comparison](../../comparison/). |

### قيمة الإرجاع

[Index](../../index/) لأخر سلسلة فرعية تم العثور عليها أو -1 إذا لم يتم العثور عليها. بالنسبة لسلسلة بحث فارغة، تُرجع دائمًا طول السلسلة.

## String::LastIndexOf(const String\&, int, int, StringComparison) const طريقة

البحث الخلفي عن سلسلة فرعية.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../)\& | السلسلة الفرعية للبحث عنها. |
| startIndex | int | الموضع في السلسلة المصدر للبدء بالبحث من خلاله. |
| count | int | عدد الأحرف للبحث من خلالها. |
| comparisonType | [StringComparison](../../stringcomparison/) | وضع [Comparison](../../comparison/). |

### قيمة الإرجاع

[Index](../../index/) لأخر سلسلة فرعية تم العثور عليها أو -1 إذا لم يتم العثور عليها. بالنسبة لسلسلة بحث فارغة، تُرجع دائمًا startIndex+count.

## String::LastIndexOf(char_t) const طريقة

البحث الخلفي عن حرف.

```cpp
int System::String::LastIndexOf(char_t value) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char_t | الحرف للبحث عنه. |

### قيمة الإرجاع

[Index](../../index/) لموقع آخر حرف تم العثور عليه أو -1 إذا لم يتم العثور عليه.

## String::LastIndexOf(char_t, int32_t) const طريقة

البحث الخلفي عن حرف.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char_t | الحرف للبحث عنه. |
| startIndex | **int32_t** | [Index](../../index/) للبدء بالبحث عنده. |

### قيمة الإرجاع

[Index](../../index/) لموقع آخر حرف منذ startIndex أو -1 إذا لم يتم العثور عليه.

## String::LastIndexOf(char_t, int32_t, int32_t) const طريقة

البحث الخلفي عن حرف.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char_t | الحرف للبحث عنه. |
| startIndex | **int32_t** | [Index](../../index/) للبدء بالبحث عنده. |
| count | **int32_t** | عدد الأحرف للبحث من خلالها |

### قيمة الإرجاع

[Index](../../index/) لموقع آخر حرف منذ startIndex أو -1 إذا لم يتم العثور عليه.

## انظر أيضاً

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)