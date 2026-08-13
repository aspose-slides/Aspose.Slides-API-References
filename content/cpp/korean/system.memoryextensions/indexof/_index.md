---
title: IndexOf()
second_title: Aspose.Slides for C++ API 참조
description: 다른 ReadOnlySpan<T>에서 ReadOnlySpan<T> 값의 인덱스를 찾습니다
type: docs
weight: 144
url: /ko/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

ReadOnlySpan<T> 값의 인덱스를 다른 ReadOnlySpan<T>에서 찾습니다

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색 대상 스팬 |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색 대상 스팬 |

### 반환 값

첫 번째 항목이 나타나는 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) 함수

ReadOnlySpan<T>에서 단일 값의 인덱스를 찾습니다

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색 대상 스팬 |
| value | const T\& | 검색할 값 |

### 반환 값

첫 번째 항목이 나타나는 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

Span<T>에서 ReadOnlySpan<T> 값의 인덱스를 찾습니다

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색 대상 스팬 |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색 대상 스팬 |

### 반환 값

첫 번째 항목이 나타나는 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) 함수

Span<T>에서 단일 값의 인덱스를 찾습니다

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색 대상 스팬 |
| value | const T\& | 검색할 값 |

### 반환 값

첫 번째 항목이 나타나는 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 함수

StringComparison을 사용하여 ReadOnlySpan<char16_t> 값의 인덱스를 ReadOnlySpan<char16_t>에서 찾습니다.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 검색 대상 스팬 |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 검색 대상 스팬 |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 사용할 문자열 비교 유형 |

### 반환 값

첫 번째 항목이 나타나는 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다

## 참조

* 열거형 [StringComparison](../../system/stringcomparison/)
* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)