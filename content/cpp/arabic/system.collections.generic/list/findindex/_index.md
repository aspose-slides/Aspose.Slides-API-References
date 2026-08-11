---
title: FindIndex()
second_title: مرجع API Aspose.Slides للغة C++
description: يبحث عن العنصر الذي يطابق شرطًا محددًا.
type: docs
weight: 404
url: /ar/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) طريقة

يبحث عن العنصر الذي يطابق الشرط المحدد.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | الشرط للتحقق من العناصر. |

### قيمة الإرجاع

[Index](../../../system/index/) للعنصر المطابق أو -1 إذا لم يُعثر عليه.

## List::FindIndex(int, System::Predicate\<T\>) طريقة

يبحث عن العنصر الذي يطابق الشرط المحدد.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) للبدء بالبحث من. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | الشرط للتحقق من العناصر. |

### قيمة الإرجاع

[Index](../../../system/index/) للعنصر المطابق أو -1 إذا لم يُعثر عليه.

## List::FindIndex(int, int, System::Predicate\<T\>) طريقة

يبحث عن العنصر الذي يطابق الشرط المحدد.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) للبدء بالبحث من. |
| count | int | عدد العناصر التي سيتم البحث خلالها. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | الشرط للتحقق من العناصر. |

### قيمة الإرجاع

[Index](../../../system/index/) للعنصر المطابق أو -1 إذا لم يُعثر عليه.

## أنظر أيضاً

* Typedef [Predicate](../../../system/predicate/)
* فئة [List](../)
* نطاق [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)