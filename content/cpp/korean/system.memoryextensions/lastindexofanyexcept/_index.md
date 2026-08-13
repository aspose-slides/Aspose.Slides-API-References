---
title: LastIndexOfAnyExcept()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 세 개 값을 제외한 모든 요소의 마지막 발생을 span 내에서 찾습니다.
type: docs
weight: 235
url: /ko/system.memoryextensions/lastindexofanyexcept/
---
## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

지정된 세 개 값을 제외한 모든 요소의 마지막 발생을 span 내에서 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | The type of elements in the span |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 span |
| value0 | const T\& | 제외할 첫 번째 값 |
| value1 | const T\& | 제외할 두 번째 값 |
| value2 | const T\& | 제외할 세 번째 값 |

### 반환 값

제외되지 않은 마지막 요소의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) function

지정된 세 개 값을 제외한 모든 요소의 마지막 발생을 가변 span 내에서 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | The type of elements in the span |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 span |
| value0 | const T\& | 제외할 첫 번째 값 |
| value1 | const T\& | 제외할 두 번째 값 |
| value2 | const T\& | 제외할 세 번째 값 |

### 반환 값

제외되지 않은 마지막 요소의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

지정된 두 개 값을 제외한 모든 요소의 마지막 발생을 span 내에서 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | The type of elements in the span |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 span |
| value0 | const T\& | 제외할 첫 번째 값 |
| value1 | const T\& | 제외할 두 번째 값 |

### 반환 값

제외되지 않은 마지막 요소의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) function

지정된 두 개 값을 제외한 모든 요소의 마지막 발생을 가변 span 내에서 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | The type of elements in the span |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 span |
| value0 | const T\& | 제외할 첫 번째 값 |
| value1 | const T\& | 제외할 두 번째 값 |

### 반환 값

제외되지 않은 마지막 요소의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) function

지정된 값을 제외한 모든 요소의 마지막 발생을 span 내에서 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | The type of elements in the span |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 span |
| value | const T\& | 제외할 값 |

### 반환 값

제외되지 않은 마지막 요소의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&) function

지정된 값을 제외한 모든 요소의 마지막 발생을 가변 span 내에서 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | The type of elements in the span |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 span |
| value | const T\& | 제외할 값 |

### 반환 값

제외되지 않은 마지막 요소의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

시퀀스의 값들을 제외한 모든 요소의 마지막 발생을 span 내에서 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | The type of elements in the span |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 제외할 값들의 시퀀스 |

### 반환 값

제외되지 않은 마지막 요소의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

시퀀스의 값들을 제외한 모든 요소의 마지막 발생을 가변 span 내에서 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | The type of elements in the span |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 제외할 값들의 시퀀스 |

### 반환 값

제외되지 않은 마지막 요소의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const Span\<T\>\&) function

가변 시퀀스의 값들을 제외한 모든 요소의 마지막 발생을 가변 span 내에서 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const Span<T> &values)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | The type of elements in the span |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 span |
| values | const [Span](../../system/span/)\<T\>\& | 제외할 값들의 시퀀스 |

### 반환 값

제외되지 않은 마지막 요소의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## 참고

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)