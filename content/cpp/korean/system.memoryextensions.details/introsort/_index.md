---
title: IntroSort()
second_title: Aspose.Slides for C++ API 참조
description: 키-값 쌍에 대한 introsort 알고리즘의 내부 구현입니다.
type: docs
weight: 40
url: /ko/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) 함수

키-값 쌍에 대한 introsort 알고리즘의 내부 구현입니다.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TKey | 키의 유형 |
| TValue | 값의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 정렬할 키의 span |
| values | [Span](../../system/span/)\<TValue\>\& | 정렬할 값의 span |
| depthLimit | **int32_t** | 힙 정렬로 전환하기 전의 최대 재귀 깊이 |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 키용 함수 |

## 참조

* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions::Details](../)
* 라이브러리 [Aspose.Slides](../../)