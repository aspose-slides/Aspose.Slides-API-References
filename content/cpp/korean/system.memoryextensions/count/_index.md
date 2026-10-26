---
title: Count()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 읽기 전용 span에서 값이 나타나는 횟수를 셉니다.
type: docs
weight: 118
url: /ko/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) 함수

읽기 전용 span에서 값이 나타나는 횟수를 셉니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span의 요소 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 span |
| value | const T\& | 카운트할 값 |

### 반환 값

span에 value가 나타나는 횟수

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

읽기 전용 span 내에서 다른 span이 나타나는 횟수를 셉니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span들의 요소 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 카운트할 span |

### 반환 값

span에 value가 나타나는 횟수

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) 함수

Span<T>에서 단일 값이 나타나는 횟수를 셉니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span의 요소 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 span |
| value | const T\& | 카운트할 값 |

### 반환 값

span에서 value의 발생 횟수

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

Span<T>에서 ReadOnlySpan<T>가 나타나는 횟수를 셉니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span들의 요소 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 카운트할 값을 포함하는 span |

### 반환 값

대상 span에서 value span의 발생 횟수

## 참고

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)