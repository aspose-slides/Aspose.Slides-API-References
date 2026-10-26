---
title: IndexOfAny()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: بحث أمامي عن الحرف.
type: docs
weight: 638
url: /ar/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const طريقة

بحث أمامي عن الحرف.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| c | char_t | الحرف للبحث عنه. |
| startIndex | int | [Index](../../index/) لبدء البحث عند. |

### قيمة الإرجاع

[Index](../../index/) لموقع أول حرف منذ startIndex أو -1 إذا لم يُعثر عليه.

## String::IndexOfAny(const String\&, int) const طريقة

بالتالي يبحث عن جميع أحرف str في هذا. إذا وُجد الحرف الأول، يتم إرجاع موقعه، وإلا يبحث عن الثاني وهكذا.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) من الأحرف للبحث عنها. ترتيب الأحرف مهم. |
| startIndex | int | الموقع لبدء البحث منه. |

### قيمة الإرجاع

[Index](../../index/) لأول حرف تم العثور عليه أو -1 إذا لم يُعثر على أي.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const طريقة

يبحث عن أي من الأحرف الممررة عبر السلسلة بأكملها. يقارن الحرف الأول في السلسلة بجميع الأحرف في anyOf، ثم يقارن الثاني وهكذا. يرجع فهرس أول حرف يطابق أيًا من الأحرف المستهدفة.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) من الأحرف للبحث عنها. ترتيب الأحرف غير مهم. |

### قيمة الإرجاع

[Index](../../index/) لأول حرف يطابق أو -1 إذا لم يُعثر عليه.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const طريقة

يبحث عن أي من الأحرف الممررة عبر الجزء الفرعي من السلسلة. يقارن الحرف الأول في السلسلة بجميع الأحرف في anyOf، ثم يقارن الثاني وهكذا. يرجع فهرس أول حرف يطابق أيًا من الأحرف المستهدفة.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) من الأحرف للبحث عنها. ترتيب الأحرف غير مهم. |
| startindex | **int32_t** | [Index](../../index/) لبدء البحث منه. |

### قيمة الإرجاع

[Index](../../index/) لأول حرف يطابق أو -1 إذا لم يُعثر عليه.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const طريقة

يبحث عن أي من الأحرف الممررة عبر الجزء الفرعي من السلسلة. يقارن الحرف الأول في السلسلة بجميع الأحرف في anyOf، ثم يقارن الثاني وهكذا. يرجع فهرس أول حرف يطابق أيًا من الأحرف المستهدفة.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) من الأحرف للبحث عنها. ترتيب الأحرف غير مهم. |
| startindex | **int32_t** | [Index](../../index/) لبدء البحث منه. |
| count | **int32_t** | عدد الأحرف للبحث عبرها. |

### قيمة الإرجاع

[Index](../../index/) لأول حرف يطابق أو -1 إذا لم يُعثر عليه.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* فئة [String](../)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)