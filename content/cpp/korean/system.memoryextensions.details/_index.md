---
title: "System::MemoryExtensions::Details"
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 638
url: /ko/system.memoryextensions.details/
---
## 함수

| Function | Description |
| --- | --- |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<U\>\&) | 두 스마트 포인터를 비교합니다. |
| **int32_t** [Compare](./compare/)(const T\&, const T\&) | 두 산술 값을 비교합니다. |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const U\&) | 스마트 포인터와 값을 비교합니다. |
| **int32_t** [LastIndexOfImpl](./lastindexofimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**, const T\&) | span에서 값의 마지막 인덱스를 찾습니다. |
| **bool** [SequenceEqualImpl](./sequenceequalimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const **int32_t**, **int32_t**, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 지정된 위치부터 두 span이 같은지 확인합니다. |
| void [IntroSort](./introsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | 키-값 쌍에 대한 introsort 알고리즘의 내부 구현입니다. |
| void [SwapIfGreaterWithValues](./swapifgreaterwithvalues/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>, **int32_t**, **int32_t**) | 비교 조건이 충족되면 키-값 쌍을 교환합니다. |
| void [InsertionSort](./insertionsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | 키-값 쌍에 대해 삽입 정렬을 수행합니다. |
| void [HeapSort](./heapsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | 키-값 쌍에 대해 힙 정렬을 수행합니다. |
| void [Heapify](./heapify/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | 키-값 쌍에 대한 힙 속성을 유지합니다. |
| **int32_t** [PickPivotAndPartition](./pickpivotandpartition/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | 퀵소트를 위해 피벗을 선택하고 키-값 쌍을 분할합니다. |
| **int32_t** [BinarySearchImpl](./binarysearchimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TValue\&, TCompareFunc) | 일반적인 이진 검색 구현입니다. |