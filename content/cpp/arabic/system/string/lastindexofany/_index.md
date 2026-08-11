---
title: LastIndexOfAny()
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++
description: يبحث عن أي من الأحرف الممرَّة عبر السلسلة بأكملها من الخلف. يقارن الحرف الأخير في السلسلة مع جميع الأحرف في anyOf، ثم يقارن الحرف السابق وهكذا. يُعيد فهرس أول تطابق يتم العثور عليه.
type: docs
weight: 664
url: /ar/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const طريقة

يبحث عن أي من الأحرف المُمرَّة عبر السلسلة بأكملها باتجاه الخلف. يقارن الحرف الأخير في السلسلة مع جميع الأحرف في anyOf، ثم يقارن السابق وهكذا. يُعيد فهرس أول تطابق تم العثور عليه.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) من الأحرف للبحث عنها. الترتيب لا يهم. |

### قيمة الإرجاع

[Index](../../index/) لأخر حرف متطابق أو -1 إذا لم يُعثر عليه.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const طريقة

يبحث عن أي من الأحرف المُمرَّة عبر الجزء الفرعي باتجاه الخلف. يقارن الحرف الأخير في السلسلة مع جميع الأحرف في anyOf، ثم يقارن السابق وهكذا. يُعيد فهرس أول تطابق تم العثور عليه.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) من الأحرف للبحث عنها. الترتيب لا يهم. |
| startindex | **int32_t** | [Index](../../index/) للبدء بالبحث من. |

### قيمة الإرجاع

[Index](../../index/) لأخر حرف متطابق أو -1 إذا لم يُعثر عليه.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const طريقة

يبحث عن أي من الأحرف المُمرَّة عبر الجزء الفرعي باتجاه الخلف. يقارن الحرف الأخير في السلسلة مع جميع الأحرف في anyOf، ثم يقارن السابق وهكذا. يُعيد فهرس أول تطابق تم العثور عليه.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) من الأحرف للبحث عنها. الترتيب لا يهم. |
| startindex | **int32_t** | [Index](../../index/) للبدء بالبحث من. |
| count | **int32_t** | عدد الأحرف للبحث خلالها. |

### قيمة الإرجاع

[Index](../../index/) لأخر حرف متطابق أو -1 إذا لم يُعثر عليه.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* فئة [String](../)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)