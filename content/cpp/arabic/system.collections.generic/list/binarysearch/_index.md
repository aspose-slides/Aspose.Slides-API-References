---
title: BinarySearch()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يبحث عن العنصر في قائمة مرتبة.
type: docs
weight: 339
url: /ar/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const طريقة

يبحث عن العنصر في قائمة مرتبة.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| item | const T\& | العنصر المراد البحث عنه. |

### قيمة الإرجاع

[Index](../../../system/index/) للعنصر في قائمة مرتبة أو مكمل أقرب فهرس.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const طريقة

يبحث عن العنصر في قائمة مرتبة.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| item | const T\& | العنصر المراد البحث عنه. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) للاستخدام. |

### قيمة الإرجاع

[Index](../../../system/index/) للعنصر في قائمة مرتبة أو مكمل أقرب فهرس.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const طريقة

يبحث عن العنصر في قائمة مرتبة.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) البداية. |
| count | int | [Range](../../../system/range/) الحجم. |
| item | const T\& | العنصر المراد البحث عنه. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) للاستخدام. |

### قيمة الإرجاع

[Index](../../../system/index/) للعنصر في قائمة مرتبة أو مكمل أقرب فهرس.

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [List](../)
* فئة [IComparer](../../icomparer/)
* نطاق [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)