---
title: InsertionSort()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 키-값 쌍에 대해 삽입 정렬을 수행합니다.
type: docs
weight: 66
url: /ko/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) 함수

키-값 쌍에 대해 삽입 정렬을 수행합니다.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TKey | 키의 유형 |
| TValue | 값의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 정렬할 키의 스팬 |
| values | [Span](../../system/span/)\<TValue\>\& | 정렬할 값의 스팬 |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 키에 대한 함수 |

## 참조

* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions::Details](../)
* 라이브러리 [Aspose.Slides](../../)