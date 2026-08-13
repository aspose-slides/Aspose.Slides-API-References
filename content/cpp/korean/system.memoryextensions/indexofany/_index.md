---
title: IndexOfAny()
second_title: Aspose.Slides for C++ API 레퍼런스
description: ReadOnlySpan<T>에서 지정된 두 값 중 하나가 처음 나타나는 인덱스를 찾습니다.
type: docs
weight: 157
url: /ko/system.memoryextensions/indexofany/
---
## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

ReadOnlySpan<T>에서 지정된 두 값 중 하나가 처음 나타나는 인덱스를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 스팬 |
| value0 | const T\& | 첫 번째 검색 값 |
| value1 | const T\& | 두 번째 검색 값 |

### 반환 값

첫 번째 발생 위치의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

ReadOnlySpan<T>에서 지정된 세 값 중 하나가 처음 나타나는 인덱스를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 스팬 |
| value0 | const T\& | 첫 번째 검색 값 |
| value1 | const T\& | 두 번째 검색 값 |
| value2 | const T\& | 세 번째 검색 값 |

### 반환 값

첫 번째 발생 위치의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&) function

Span<T>에서 지정된 두 값 중 하나가 처음 나타나는 인덱스를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 스팬 |
| value0 | const T\& | 첫 번째 검색 값 |
| value1 | const T\& | 두 번째 검색 값 |

### 반환 값

첫 번째 발생 위치의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) function

Span<T>에서 지정된 세 값 중 하나가 처음 나타나는 인덱스를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 스팬 |
| value0 | const T\& | 첫 번째 검색 값 |
| value1 | const T\& | 두 번째 검색 값 |
| value2 | const T\& | 세 번째 검색 값 |

### 반환 값

첫 번째 발생 위치의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

다른 ReadOnlySpan<T>에서 span에 포함된 값 중 하나가 처음 나타나는 인덱스를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 스팬 |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 값이 포함된 스팬 |

### 반환 값

첫 번째 발생 위치의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Span<T>에서 span에 포함된 값 중 하나가 처음 나타나는 인덱스를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 스팬 |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 값이 포함된 스팬 |

### 반환 값

첫 번째 발생 위치의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## 또 보기

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)