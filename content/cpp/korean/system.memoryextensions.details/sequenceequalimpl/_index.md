---
title: SequenceEqualImpl()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 위치에서 시작하여 두 스팬이 동일한지 확인합니다.
type: docs
weight: 27
url: /ko/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) function

두 스팬이 지정된 위치에서 시작하여 동일한지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬의 요소 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 첫 번째 스팬 |
| start | const **int32_t** | 첫 번째 스팬의 시작 인덱스 |
| length | **int32_t** | 비교할 요소 수 |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 두 번째 스팬 |

### 반환 값

지정된 범위가 동일하면 true, 그렇지 않으면 false

## 참고

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 네임스페이스 [System::MemoryExtensions::Details](../)
* 라이브러리 [Aspose.Slides](../../)