---
title: TrimEnd()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 타입화된 Span의 끝에서 지정된 요소를 제거합니다.
type: docs
weight: 378
url: /ko/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) function

지정된 요소를 타입화된 Span의 끝에서 제거합니다.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Span 내 요소들의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 잘라낼 Span |
| trimElement | const T\& | 잘라낼 요소 |

### 반환값

지정된 요소가 끝에서 제거된 새로운 Span

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) function

변경 가능한 타입화된 Span의 끝에서 지정된 요소를 제거합니다.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Span 내 요소들의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 잘라낼 변경 가능한 Span |
| trimElement | const T\& | 잘라낼 요소 |

### 반환값

지정된 요소가 끝에서 제거된 새로운 Span

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

지정된 요소들을 타입화된 Span의 끝에서 제거합니다.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Span 내 요소들의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 잘라낼 Span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 잘라낼 요소들 |

### 반환값

지정된 요소들이 끝에서 제거된 새로운 Span

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

변경 가능한 타입화된 Span의 끝에서 지정된 요소들을 제거합니다.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Span 내 요소들의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 잘라낼 변경 가능한 Span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 잘라낼 요소들 |

### 반환값

지정된 요소들이 끝에서 제거된 새로운 Span

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) function

문자 Span의 끝에서 공백 문자를 제거합니다.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 잘라낼 문자 Span |

### 반환값

끝에서 공백이 제거된 새로운 Span

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) function

변경 가능한 문자 Span의 끝에서 공백 문자를 제거합니다.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | 잘라낼 변경 가능한 문자 Span |

### 반환값

끝에서 공백이 제거된 새로운 Span

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) function

문자 Span의 끝에서 지정된 문자를 제거합니다.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 잘라낼 문자 Span |
| trimchar | char16_t | 잘라낼 문자 |

### 반환값

지정된 문자가 끝에서 제거된 새로운 Span

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) function

변경 가능한 문자 Span의 끝에서 지정된 문자를 제거합니다.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | 잘라낼 변경 가능한 문자 Span |
| trimchar | char16_t | 잘라낼 문자 |

### 반환값

지정된 문자가 끝에서 제거된 새로운 Span

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

문자 Span의 끝에서 지정된 문자들을 제거합니다.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 잘라낼 문자 Span |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 잘라낼 문자들 |

### 반환값

지정된 문자들이 끝에서 제거된 새로운 Span

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

변경 가능한 문자 Span의 끝에서 지정된 문자들을 제거합니다.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | 잘라낼 변경 가능한 문자 Span |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 잘라낼 문자들 |

### 반환값

지정된 문자들이 끝에서 제거된 새로운 Span

## 참조

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)