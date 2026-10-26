---
title: SwapIfGreaterWithValues()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 비교 조건이 충족되면 키-값 쌍을 교환합니다.
type: docs
weight: 53
url: /ko/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) function

비교 조건이 만족되면 키-값 쌍을 교환합니다.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TKey | 키의 유형 |
| TValue | 값의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 키의 span |
| values | [Span](../../system/span/)\<TValue\>\& | 값의 span |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 키에 대한 함수 |
| i | **int32_t** | 비교할 첫 번째 인덱스 |
| j | **int32_t** | 비교할 두 번째 인덱스 |

## 참조

* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions::Details](../)
* 라이브러리 [Aspose.Slides](../../)