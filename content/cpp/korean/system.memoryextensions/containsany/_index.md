---
title: ContainsAny()
second_title: Aspose.Slides for C++ API 참조
description: 읽기 전용 span에 두 값 중 어느 하나라도 포함되어 있는지 확인합니다.
type: docs
weight: 53
url: /ko/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

읽기 전용 span이 두 값 중 어느 하나라도 포함하고 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span에 있는 요소의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 span |
| value0 | const T\& | 검색할 첫 번째 값 |
| value1 | const T\& | 검색할 두 번째 값 |

### 반환값

값 중 하나라도 span에서 발견되면 true, 그렇지 않으면 false

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

읽기 전용 span이 세 값 중 어느 하나라도 포함하고 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span에 있는 요소의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 span |
| value0 | const T\& | 검색할 첫 번째 값 |
| value1 | const T\& | 검색할 두 번째 값 |
| value2 | const T\& | 검색할 세 번째 값 |

### 반환값

값 중 하나라도 span에서 발견되면 true, 그렇지 않으면 false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) function

가변 span이 두 값 중 어느 하나라도 포함하고 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span에 있는 요소의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 가변 span |
| value0 | const T\& | 검색할 첫 번째 값 |
| value1 | const T\& | 검색할 두 번째 값 |

### 반환값

값 중 하나라도 span에서 발견되면 true, 그렇지 않으면 false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) function

가변 span이 세 값 중 어느 하나라도 포함하고 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span에 있는 요소의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 가변 span |
| value0 | const T\& | 검색할 첫 번째 값 |
| value1 | const T\& | 검색할 두 번째 값 |
| value2 | const T\& | 검색할 세 번째 값 |

### 반환값

값 중 하나라도 span에서 발견되면 true, 그렇지 않으면 false

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

읽기 전용 span이 다른 span에 있는 값 중 어느 하나라도 포함하고 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span들의 요소 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 값들의 span |

### 반환값

값 중 하나라도 span에서 발견되면 true, 그렇지 않으면 false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

가변 span이 읽기 전용 span에 있는 값 중 어느 하나라도 포함하고 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span들의 요소 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 가변 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 읽기 전용 값들의 span |

### 반환값

값 중 하나라도 span에서 발견되면 true, 그렇지 않으면 false

## 참고

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)