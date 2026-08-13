---
title: LastIndexOfAny()
second_title: Aspose.Slides for C++ API 레퍼런스
description: span 내에서 지정된 세 값 중 하나가 마지막으로 나타나는 위치를 찾습니다.
type: docs
weight: 222
url: /ko/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) 함수

지정된 세 값 중 하나가 span 내에 마지막으로 나타나는 위치를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |
| value2 | const T\& | The third value to search for |

### 반환 값

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) 함수

가변 span 내에서 지정된 세 값 중 하나가 마지막으로 나타나는 위치를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |
| value2 | const T\& | The third value to search for |

### 반환 값

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 함수

지정된 두 값 중 하나가 span 내에 마지막으로 나타나는 위치를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |

### 반환 값

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) 함수

가변 span 내에서 지정된 두 값 중 하나가 마지막으로 나타나는 위치를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |

### 반환 값

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

시퀀스의 모든 값 중 하나가 span 내에 마지막으로 나타나는 위치를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to search for |

### 반환 값

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

가변 span 내에서 시퀀스의 모든 값 중 하나가 마지막으로 나타나는 위치를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to search for |

### 반환 값

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) 함수

가변 span 내에서 가변 시퀀스의 모든 값 중 하나가 마지막으로 나타나는 위치를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [Span](../../system/span/)\<T\>\& | The sequence of values to search for |

### 반환 값

The zero-based index of the last occurrence, or -1 if not found

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)