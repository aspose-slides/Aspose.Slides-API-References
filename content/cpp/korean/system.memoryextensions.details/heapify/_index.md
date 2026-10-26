---
title: Heapify()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 키-값 쌍에 대한 힙 속성을 유지합니다.
type: docs
weight: 92
url: /ko/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) 함수

키-값 쌍에 대한 힙 속성을 유지합니다.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TKey | 키의 유형 |
| TValue | 값의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 힙에 있는 키의 span |
| values | [Span](../../system/span/)\<TValue\>\& | 힙에 있는 값의 span |
| n | **int32_t** | 힙의 크기 |
| i | **int32_t** | [Index](../../system/index/)부터 heapify |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 키에 대한 함수 |

## 참조

* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions::Details](../)
* 라이브러리 [Aspose.Slides](../../)