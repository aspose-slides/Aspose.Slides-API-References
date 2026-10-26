---
title: IndexOf()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: بحث أمامي عن سلسلة فرعية.
type: docs
weight: 625
url: /ar/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const طريقة

البحث الأمامي عن سلسلة فرعية.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../)\& | السلسلة الفرعية التي يبحث عنها. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) وضع. |

### قيمة الإرجاع

[Index](../../index/) من أول سلسلة فرعية تم العثور عليها أو -1 إذا لم تُعثر. بالنسبة لسلسلة البحث الفارغة، تُرجع دائمًا 0.

## String::IndexOf(char_t, int) const طريقة

بحث أمامي عن حرف.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| c | char_t | الحرف الذي يبحث عنه. |
| startIndex | int | [Index](../../index/) لبدء البحث عند. |

### قيمة الإرجاع

[Index](../../index/) من موقع أول حرف منذ startIndex أو -1 إذا لم يُعثر.

## String::IndexOf(char_t, int, int) const طريقة

بحث أمامي عن حرف في سلسلة فرعية.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| c | char_t | الحرف الذي يبحث عنه. |
| startIndex | int | [Index](../../index/) لبدء البحث عند. |
| count | int | عدد الأحرف للبحث عبرها. |

### قيمة الإرجاع

[Index](../../index/) من موقع أول حرف منذ startIndex أو -1 إذا لم يُعثر.

## String::IndexOf(const String\&, int) const طريقة

البحث الأمامي عن سلسلة فرعية.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../)\& | السلسلة الفرعية التي يبحث عنها. |
| startIndex | int | الموضع في السلسلة الأصلية لبدء البحث من خلاله. |

### قيمة الإرجاع

[Index](../../index/) من أول سلسلة فرعية تم العثور عليها أو -1 إذا لم تُعثر. بالنسبة لسلسلة البحث الفارغة، تُرجع دائمًا startIndex.

## String::IndexOf(const String\&, int, System::StringComparison) const طريقة

البحث الأمامي عن سلسلة فرعية.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../)\& | السلسلة الفرعية التي يبحث عنها. |
| startIndex | int | الموضع في السلسلة الأصلية لبدء البحث من خلاله. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) وضع. |

### قيمة الإرجاع

[Index](../../index/) من أول سلسلة فرعية تم العثور عليها أو -1 إذا لم تُعثر. بالنسبة لسلسلة البحث الفارغة، تُرجع دائمًا startIndex.

## String::IndexOf(const String\&, int, int, System::StringComparison) const طريقة

البحث الأمامي عن سلسلة فرعية.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../)\& | السلسلة الفرعية التي يبحث عنها. |
| startIndex | int | الموضع في السلسلة الأصلية لبدء البحث من خلاله. |
| count | int | عدد الأحرف للبحث عبرها. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) وضع. |

### قيمة الإرجاع

[Index](../../index/) من أول سلسلة فرعية تم العثور عليها أو -1 إذا لم تُعثر. بالنسبة لسلسلة البحث الفارغة، تُرجع دائمًا startIndex.

## String::IndexOf(const String\&, int, int) const طريقة

البحث الأمامي عن سلسلة فرعية.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../)\& | السلسلة الفرعية التي يبحث عنها. |
| startIndex | int | الموضع في السلسلة الأصلية لبدء البحث من خلاله. |
| count | int | عدد الأحرف للبحث عبرها. |

### قيمة الإرجاع

[Index](../../index/) من أول سلسلة فرعية تم العثور عليها أو -1 إذا لم تُعثر. بالنسبة لسلسلة البحث الفارغة، تُرجع دائمًا startIndex.

## أنظر أيضًا

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)