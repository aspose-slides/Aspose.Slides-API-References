---
title: LastIndexOfImpl()
second_title: Aspose.Slides C++ API 레퍼런스
description: 스팬에서 값의 마지막 인덱스를 찾습니다.
type: docs
weight: 14
url: /ko/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) 함수

스팬에서 값의 마지막 인덱스를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Span 안의 요소 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) 검색 대상 |
| length | **int32_t** | 검색할 길이 |
| value | const T\& | 찾을 값 |

### 반환값

값의 마지막 인덱스, 찾지 못하면 -1

## 참고

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 네임스페이스 [System::MemoryExtensions::Details](../)
* 라이브러리 [Aspose.Slides](../../)