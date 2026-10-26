---
title: SequenceCompareTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 두 ReadOnlySpan을 사전식으로 비교합니다.
type: docs
weight: 313
url: /ko/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

두 ReadOnlySpan을 사전식으로 비교합니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | spans에 있는 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 비교할 첫 번째 span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 비교할 두 번째 span |

### 반환 값

- 1 (span < other인 경우), 0 (span == other인 경우), 1 (span > other인 경우)

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

사전식으로 [Span](../../system/span/)와 [ReadOnlySpan](../../system/readonlyspan/)를 비교합니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | spans에 있는 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 비교할 [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 비교할 [ReadOnlySpan](../../system/readonlyspan/) |

### 반환 값

- 1 (span < other인 경우), 0 (span == other인 경우), 1 (span > other인 경우)

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) 함수

사전식으로 [ReadOnlySpan](../../system/readonlyspan/)와 [Span](../../system/span/)를 비교합니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | spans에 있는 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 비교할 [ReadOnlySpan](../../system/readonlyspan/) |
| other | const [Span](../../system/span/)\<T\>\& | 비교할 [Span](../../system/span/) |

### 반환 값

- 1 (span < other인 경우), 0 (span == other인 경우), 1 (span > other인 경우)

## 참고

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)