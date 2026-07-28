---
title: "System::MemoryExtensions::Details"
second_title: Aspose.Slides for C++ API-referencia
description: 
type: docs
weight: 638
url: /hu/system.memoryextensions.details/
---
## Függvények

| Függvény | Leírás |
| --- | --- |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<U\>\&) | Két okos mutatót hasonlít össze. |
| **int32_t** [Compare](./compare/)(const T\&, const T\&) | Két aritmetikai értéket hasonlít össze. |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const U\&) | Okos mutatót értékkel hasonlít össze. |
| **int32_t** [LastIndexOfImpl](./lastindexofimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**, const T\&) | Megkeresi egy érték utolsó indexét egy tartományban. |
| **bool** [SequenceEqualImpl](./sequenceequalimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const **int32_t**, **int32_t**, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Ellenőrzi, hogy két tartomány egyenlő-e a megadott pozícióktól kezdve. |
| void [IntroSort](./introsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Kulcs-érték párok introsort algoritmusának belső megvalósítása. |
| void [SwapIfGreaterWithValues](./swapifgreaterwithvalues/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>, **int32_t**, **int32_t**) | Kicseréli a kulcs-érték párokat, ha a összehasonlítási feltétel teljesül. |
| void [InsertionSort](./insertionsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Beszúró rendezést hajt végre a kulcs-érték párokon. |
| void [HeapSort](./heapsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Halmazrendezést hajt végre a kulcs-érték párokon. |
| void [Heapify](./heapify/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Fenntartja a halmaz tulajdonságát a kulcs-érték párok esetén. |
| **int32_t** [PickPivotAndPartition](./pickpivotandpartition/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Kiválaszt egy pivotot és felosztja a kulcs-érték párokat a gyorsrendezéshez. |
| **int32_t** [BinarySearchImpl](./binarysearchimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TValue\&, TCompareFunc) | Általános bináris keresés megvalósítása. |