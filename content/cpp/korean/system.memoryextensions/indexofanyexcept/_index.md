---
title: IndexOfAnyExcept()
second_title: Aspose.Slides for C++ API 레퍼런스
description: ReadOnlySpan<T>에서 지정된 값과 같지 않은 첫 번째 요소의 인덱스를 찾습니다.
type: docs
weight: 170
url: /ko/system.memoryextensions/indexofanyexcept/
---
## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) 함수

ReadOnlySpan<T>에서 지정된 값과 같지 않은 첫 번째 요소의 인덱스를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const T\& | The value to exclude from the search |

### 반환 값

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 함수

ReadOnlySpan<T>에서 두 개의 지정된 값 중 어느 것과도 같지 않은 첫 번째 요소의 인덱스를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude from the search |
| value1 | const T\& | The second value to exclude from the search |

### 반환 값

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) 함수

ReadOnlySpan<T>에서 세 개의 지정된 값 중 어느 것과도 같지 않은 첫 번째 요소의 인덱스를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude from the search |
| value1 | const T\& | The second value to exclude from the search |
| value2 | const T\& | The third value to exclude from the search |

### 반환 값

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&) 함수

Span<T>에서 지정된 값과 같지 않은 첫 번째 요소의 인덱스를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value | const T\& | The value to exclude from the search |

### 반환 값

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) 함수

Span<T>에서 두 개의 지정된 값 중 어느 것과도 같지 않은 첫 번째 요소의 인덱스를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude from the search |
| value1 | const T\& | The second value to exclude from the search |

### 반환 값

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) 함수

Span<T>에서 세 개의 지정된 값 중 어느 것과도 같지 않은 첫 번째 요소의 인덱스를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude from the search |
| value1 | const T\& | The second value to exclude from the search |
| value2 | const T\& | The third value to exclude from the search |

### 반환 값

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

값이 포함된 span 중 어느 값과도 같지 않은 첫 번째 요소의 인덱스를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span containing values to exclude from the search |

### 반환 값

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

Span<T>에서 값이 포함된 span 중 어느 값과도 같지 않은 첫 번째 요소의 인덱스를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span containing values to exclude from the search |

### 반환 값

The zero-based index of the first non-matching element, or -1 if not found

## 참고

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)