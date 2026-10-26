---
title: HeapSort()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 키-값 쌍에 대해 힙 정렬을 수행합니다.
type: docs
weight: 79
url: /ko/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) 함수

키-값 쌍에 대해 힙 정렬을 수행합니다.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| TKey | 키의 유형 |
| TValue | 값의 유형 |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 정렬할 키의 span |
| values | [Span](../../system/span/)\<TValue\>\& | 정렬할 값의 span |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | 키에 대한 [Comparison](../../system/comparison/) 함수 |

## 참고

* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)