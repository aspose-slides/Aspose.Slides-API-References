---
title: LastIndexOfAnyExceptInRange()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 스팬 내에서 지정된 범위 밖에 있는 모든 요소의 마지막 발생을 찾습니다.
type: docs
weight: 248
url: /ko/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\>) 함수

스팬 내에서 지정된 범위 밖에 있는 모든 요소의 마지막 발생을 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 스팬 |
| lowInclusive | const T\& | 범위의 하한 (포함) |
| highInclusive | const T\& | 범위의 상한 (포함) |

### 반환 값

범위 밖에 있는 마지막 요소의 0 기반 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\>) 함수

가변 스팬 내에서 지정된 범위 밖에 있는 모든 요소의 마지막 발생을 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 스팬 |
| lowInclusive | const T\& | 범위의 하한 (포함) |
| highInclusive | const T\& | 범위의 상한 (포함) |

### 반환 값

범위 밖에 있는 마지막 요소의 0 기반 인덱스이며, 찾지 못하면 -1을 반환합니다.

## 관련 항목

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)