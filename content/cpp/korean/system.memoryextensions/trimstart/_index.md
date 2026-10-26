---
title: TrimStart()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 형식이 지정된 Span의 시작 부분에서 지정된 요소를 잘라냅니다.
type: docs
weight: 391
url: /ko/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) 함수

지정된 요소를 타입화된 Span의 시작 부분에서 잘라냅니다.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Span에서 요소의 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 잘라낼 Span |
| trimElement | const T\& | 잘라낼 요소 |

### 반환값

시작 부분에서 지정된 요소가 잘라낸 새로운 Span

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) 함수

지정된 요소를 가변 타입화된 Span의 시작 부분에서 잘라냅니다.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Span에서 요소의 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 잘라낼 가변 Span |
| trimElement | const T\& | 잘라낼 요소 |

### 반환값

시작 부분에서 지정된 요소가 잘라낸 새로운 Span

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

지정된 요소들을 타입화된 Span의 시작 부분에서 잘라냅니다.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Span에서 요소들의 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 잘라낼 Span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 잘라낼 요소들 |

### 반환값

시작 부분에서 지정된 요소들이 잘라낸 새로운 Span

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

지정된 요소들을 가변 타입화된 Span의 시작 부분에서 잘라냅니다.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Span에서 요소들의 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 잘라낼 가변 Span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 잘라낼 요소들 |

### 반환값

시작 부분에서 지정된 요소들이 잘라낸 새로운 Span

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) 함수

문자 Span의 시작 부분에서 공백 문자를 잘라냅니다.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 잘라낼 문자 Span |

### 반환값

시작 부분에서 공백이 잘라낸 새로운 Span

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) 함수

가변 문자 Span의 시작 부분에서 공백 문자를 잘라냅니다.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | 잘라낼 가변 문자 Span |

### 반환값

시작 부분에서 공백이 잘라낸 새로운 Span

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) 함수

문자 Span의 시작 부분에서 지정된 문자를 잘라냅니다.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 잘라낼 문자 Span |
| trimchar | char16_t | 잘라낼 문자 |

### 반환값

시작 부분에서 지정된 문자가 잘라낸 새로운 Span

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) 함수

가변 문자 Span의 시작 부분에서 지정된 문자를 잘라냅니다.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | 잘라낼 가변 문자 Span |
| trimchar | char16_t | 잘라낼 문자 |

### 반환값

시작 부분에서 지정된 문자가 잘라낸 새로운 Span

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) 함수

문자 Span의 시작 부분에서 지정된 문자들을 잘라냅니다.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 잘라낼 문자 Span |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 잘라낼 문자들 |

### 반환값

시작 부분에서 지정된 문자들이 잘라낸 새로운 Span

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) 함수

가변 문자 Span의 시작 부분에서 지정된 문자들을 잘라냅니다.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | 잘라낼 가변 문자 Span |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 잘라낼 문자들 |

### 반환값

시작 부분에서 지정된 문자들이 잘라낸 새로운 Span

## 또 보기

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)