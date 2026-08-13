---
title: IndexOfAnyExceptInRange()
second_title: Aspose.Slides for C++ API 레퍼런스
description: ReadOnlySpan<T>에서 지정된 범위를 벗어나는 첫 번째 요소의 인덱스를 찾습니다
type: docs
weight: 183
url: /ko/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 함수

ReadOnlySpan<T>에서 지정된 범위를 벗어나는 첫 번째 요소의 인덱스를 찾습니다

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span에 있는 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 span |
| lowInclusive | const T\& | 범위의 하한 (포함) |
| highInclusive | const T\& | 범위의 상한 (포함) |

### 반환 값

범위를 벗어나는 첫 번째 요소의 0 기반 인덱스이며, 찾지 못하면 -1을 반환합니다

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) 함수

Span<T>에서 지정된 범위를 벗어나는 첫 번째 요소의 인덱스를 찾습니다

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span에 있는 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 span |
| lowInclusive | const T\& | 범위의 하한 (포함) |
| highInclusive | const T\& | 범위의 상한 (포함) |

### 반환 값

범위를 벗어나는 첫 번째 요소의 0 기반 인덱스이며, 찾지 못하면 -1을 반환합니다

## 참조

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)