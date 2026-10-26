---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 스팬 내에서 시퀀스가 마지막으로 나타나는 위치를 찾습니다.
type: docs
weight: 209
url: /ko/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 함수


스팬 내에서 시퀀스가 마지막으로 나타나는 위치를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬의 요소 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 스팬 |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 시퀀스 |

### 반환 값

마지막 발생 위치의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) 함수


스팬 내에서 단일 값이 마지막으로 나타나는 위치를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬의 요소 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 스팬 |
| value | const T\& | 검색할 값 |

### 반환 값

마지막 발생 위치의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 함수


변경 가능한 스팬 내에서 시퀀스가 마지막으로 나타나는 위치를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬의 요소 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 스팬 |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 시퀀스 |

### 반환 값

마지막 발생 위치의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) 함수


변경 가능한 스팬 내에서 단일 값이 마지막으로 나타나는 위치를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬의 요소 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 스팬 |
| value | const T\& | 검색할 값 |

### 반환 값

마지막 발생 위치의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 함수


지정된 문자열 비교를 사용하여 스팬 내에서 값이 마지막으로 나타나는 위치를 찾습니다.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 검색할 스팬 |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 검색할 값 |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 수행할 문자열 비교 유형 |

### 반환 값

마지막 발생 위치의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## 참조

* 열거형 [StringComparison](../../system/stringcomparison/)
* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)