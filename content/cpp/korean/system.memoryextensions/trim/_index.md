---
title: Trim()
second_title: Aspose.Slides C++용 API 참조
description: 타입이 지정된 span 양쪽 끝에서 지정된 요소를 제거합니다.
type: docs
weight: 365
url: /ko/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) 함수

타입이 지정된 span의 양쪽 끝에서 지정된 요소를 제거합니다.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span에 포함된 요소의 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 제거할 span |
| trimElement | T | 제거할 요소 |

### 반환 값

양쪽 끝에서 지정된 요소가 제거된 새로운 span

## System::MemoryExtensions::Trim(Span\<T\>\&, T) 함수

가변 타입 span의 양쪽 끝에서 지정된 요소를 제거합니다.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span에 포함된 요소의 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 제거할 가변 span |
| trimElement | T | 제거할 요소 |

### 반환 값

양쪽 끝에서 지정된 요소가 제거된 새로운 span

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

타입이 지정된 span의 양쪽 끝에서 지정된 요소들을 제거합니다.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span에 포함된 요소의 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 제거할 span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 제거할 요소들 |

### 반환 값

양쪽 끝에서 지정된 요소들이 제거된 새로운 span

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

가변 타입 span의 양쪽 끝에서 지정된 요소들을 제거합니다.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span에 포함된 요소의 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 제거할 가변 span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 제거할 요소들 |

### 반환 값

양쪽 끝에서 지정된 요소들이 제거된 새로운 span

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) 함수

문자 span의 양쪽 끝에서 공백 문자를 제거합니다.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 제거할 문자 span |

### 반환 값

양쪽 끝에서 공백이 제거된 새로운 span

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) 함수

가변 문자 span의 양쪽 끝에서 공백 문자를 제거합니다.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | 제거할 가변 문자 span |

### 반환 값

양쪽 끝에서 공백이 제거된 새로운 span

## 또 보기

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)