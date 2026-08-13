---
title: IndexOfAnyInRange()
second_title: Aspose.Slides for C++ API 참조
description: ReadOnlySpan<T>에서 지정된 범위에 포함되는 첫 번째 요소의 인덱스를 찾습니다.
type: docs
weight: 196
url: /ko/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

ReadOnlySpan<T>에서 지정된 범위에 포함되는 첫 번째 요소의 인덱스를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### 반환값

The zero-based index of the first element within the range, or -1 if not found

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) function

Span<T>에서 지정된 범위에 포함되는 첫 번째 요소의 인덱스를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### 반환값

The zero-based index of the first element within the range, or -1 if not found

## 또 보기

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)