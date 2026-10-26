---
title: BinarySearch()
second_title: مرجع API Aspose.Slides برای C++
description: به دنبال یک آیتم در یک لیست مرتب می‌گردد.
type: docs
weight: 339
url: /fa/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const method

به دنبال یک آیتم در یک لیست مرتب می‌گردد.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | const T\& | آیتم برای جستجو. |

### مقدار بازگشت

[Index](../../../system/index/) مورد در لیست مرتب یا مکمل نزدیک‌ترین شاخص.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const method

به دنبال یک آیتم در یک لیست مرتب می‌گردد.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | const T\& | آیتم برای جستجو. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) برای استفاده. |

### مقدار بازگشت

[Index](../../../system/index/) مورد در لیست مرتب یا مکمل نزدیک‌ترین شاخص.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const method

به دنبال یک آیتم در یک لیست مرتب می‌گردد.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) شروع. |
| count | int | [Range](../../../system/range/) اندازه. |
| item | const T\& | آیتم برای جستجو. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) برای استفاده. |

### مقدار بازگشت

[Index](../../../system/index/) مورد در لیست مرتب یا مکمل نزدیک‌ترین شاخص.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [List](../)
* کلاس [IComparer](../../icomparer/)
* فضای‌نام [System::Collections::Generic](../../)
* کتابخانه [Aspose.Slides](../../../)