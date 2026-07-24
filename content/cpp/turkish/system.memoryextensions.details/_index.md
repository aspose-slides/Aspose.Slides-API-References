---
title: "System::MemoryExtensions::Details"
second_title: Aspose.Slides for C++ API Referansı
description: 
type: docs
weight: 638
url: /tr/system.memoryextensions.details/
---
## Fonksiyonlar

| Fonksiyon | Açıklama |
| --- | --- |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<U\>\&) | İki akıllı göstericiyi karşılaştırır. |
| **int32_t** [Compare](./compare/)(const T\&, const T\&) | İki aritmetik değeri karşılaştırır. |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const U\&) | Bir akıllı göstericiyi bir değerle karşılaştırır. |
| **int32_t** [LastIndexOfImpl](./lastindexofimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**, const T\&) | Bir span içindeki değerin son indeksini bulur. |
| **bool** [SequenceEqualImpl](./sequenceequalimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const **int32_t**, **int32_t**, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | İki span'ın belirtilen konumlardan itibaren eşit olup olmadığını kontrol eder. |
| void [IntroSort](./introsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Anahtar-değer çiftleri için introsort algoritmasının dahili uygulaması. |
| void [SwapIfGreaterWithValues](./swapifgreaterwithvalues/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>, **int32_t**, **int32_t**) | Karşılaştırma koşulu sağlandığında anahtar-değer çiftlerini takas eder. |
| void [InsertionSort](./insertionsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Anahtar-değer çiftleri üzerinde ekleme sıralaması uygular. |
| void [HeapSort](./heapsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Anahtar-değer çiftleri üzerinde yığın sıralaması uygular. |
| void [Heapify](./heapify/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Anahtar-değer çiftleri için yığın özelliğini korur. |
| **int32_t** [PickPivotAndPartition](./pickpivotandpartition/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Quicksort için pivot seçer ve anahtar-değer çiftlerini bölümlendirir. |
| **int32_t** [BinarySearchImpl](./binarysearchimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TValue\&, TCompareFunc) | Ortak ikili arama uygulaması. |