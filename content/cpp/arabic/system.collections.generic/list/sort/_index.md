---
title: Sort()
second_title: مرجع Aspose.Slides لـ C++
description: يقوم بفرز العناصر في القائمة.
type: docs
weight: 521
url: /ar/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) طريقة

يقوم بفرز العناصر في القائمة.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Comparator to use. |

## List::Sort() طريقة

يقوم بفرز العناصر في القائمة باستخدام المقارن الافتراضي.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) طريقة

يقوم بفرز جزء من القائمة.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Slice beginning index. |
| count | int | Slice size. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | Comparator to use. |

## List::Sort(Comparison\<T\>, bool) طريقة

يقوم بفرز العناصر في القائمة.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) to use. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IComparer](../../icomparer/)
* فئة [List](../)
* فئة [Comparison](../../../system/comparison/)
* نطاق [System::Collections::Generic](../../)
* مكتبة [Aspose.Slides](../../../)