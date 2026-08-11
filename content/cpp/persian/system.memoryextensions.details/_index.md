---
title: "System::MemoryExtensions::Details"
second_title: مرجع API Aspose.Slides برای C++
description: 
type: docs
weight: 638
url: /fa/system.memoryextensions.details/
---
## توابع

| تابع | توضیح |
| --- | --- |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<U\>\&) | دو اشاره‌گر هوشمند را مقایسه می‌کند. |
| **int32_t** [Compare](./compare/)(const T\&, const T\&) | دو مقدار عددی را مقایسه می‌کند. |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const U\&) | یک اشاره‌گر هوشمند را با مقدار مقایسه می‌کند. |
| **int32_t** [LastIndexOfImpl](./lastindexofimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**, const T\&) | آخرین شاخص یک مقدار را در یک بازه پیدا می‌کند. |
| **bool** [SequenceEqualImpl](./sequenceequalimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const **int32_t**, **int32_t**, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | بررسی می‌کند که آیا دو بازه از موقعیت‌های مشخص شده برابر هستند یا خیر. |
| void [IntroSort](./introsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | پیاده‌سازی داخلی الگوریتم introsort برای جفت‌های کلید-مقدار. |
| void [SwapIfGreaterWithValues](./swapifgreaterwithvalues/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>, **int32_t**, **int32_t**) | اگر شرط مقایسه برآورده شود، جفت‌های کلید-مقدار را جابجا می‌کند. |
| void [InsertionSort](./insertionsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | مرتب‌سازی درج را روی جفت‌های کلید-مقدار انجام می‌دهد. |
| void [HeapSort](./heapsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | مرتب‌سازی heap را روی جفت‌های کلید-مقدار انجام می‌دهد. |
| void [Heapify](./heapify/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | خواص heap را برای جفت‌های کلید-مقدار حفظ می‌کند. |
| **int32_t** [PickPivotAndPartition](./pickpivotandpartition/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | محور (pivot) را انتخاب کرده و جفت‌های کلید-مقدار را برای quicksort تقسیم می‌کند. |
| **int32_t** [BinarySearchImpl](./binarysearchimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TValue\&, TCompareFunc) | پیاده‌سازی معمول جستجوی دودویی. |