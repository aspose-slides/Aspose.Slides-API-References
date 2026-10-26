---
title: BinarySearch()
second_title: مرجع API Aspose.Slides برای C++
description: جستجوی دودویی را در آرایهٔ مرتب انجام می‌دهد.
type: docs
weight: 612
url: /fa/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) متد


در آرایهٔ مرتب جستجوی دودویی را انجام می‌دهد.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | آرایهٔ مرتب برای انجام جستجو |
| item | const T\& | آیتمی برای جستجو |

### مقدار بازگشت

[Index](../../index/) مورد جستجو شده اگر یافت شود، در غیر این صورت، عدد صحیح منفی که مکمل بیتی شاخص آیتم بعدی بزرگتر از مورد جستجو شده است یا، اگر آیتم بزرگتری وجود نداشته باشد، مکمل بیتی تعداد عناصر در آرایه.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) متد


پیاده‌سازی نشده.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```


## موارد مرتبط

* تعریف‌نوع [ArrayPtr](../../arrayptr/)
* تعریف‌نوع [SharedPtr](../../sharedptr/)
* کلاس [Array](../)
* کلاس [IComparer](../../../system.collections.generic/icomparer/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)