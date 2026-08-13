---
title: CommonPrefixLength()
second_title: Aspose.Slides용 C++ API 참조
description: 두 스팬 사이의 공통 접두사의 길이를 찾습니다.
type: docs
weight: 27
url: /ko/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

두 스팬 사이의 공통 접두사의 길이를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬의 요소 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 첫 번째 스팬 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 두 번째 스팬 |

### 반환 값

두 스팬 시작 부분에서 일치하는 요소의 수

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

가변 스팬과 읽기 전용 스팬 사이의 공통 접두사의 길이를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬의 요소 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 가변 스팬 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 읽기 전용 스팬 |

### 반환 값

두 스팬 시작 부분에서 일치하는 요소의 수

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) 함수

두 가변 스팬 사이의 공통 접두사의 길이를 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬의 요소 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 첫 번째 가변 스팬 |
| other | const [Span](../../system/span/)\<T\>\& | 두 번째 가변 스팬 |

### 반환 값

두 스팬 시작 부분에서 일치하는 요소의 수

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) 함수

사용자 정의 동등 비교자를 사용하여 두 스팬 사이의 공통 접두사의 길이를 찾습니다.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬의 요소 유형 |
| TEqualityComparer | 동등 비교자의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 첫 번째 스팬 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 두 번째 스팬 |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | 요소 비교에 사용할 동등 비교자 |

### 반환 값

두 스팬 시작 부분에서 일치하는 요소의 수

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) 함수

사용자 정의 동등 비교자를 사용하여 가변 스팬과 읽기 전용 스팬 사이의 공통 접두사의 길이를 찾습니다.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬의 요소 유형 |
| TEqualityComparer | 동등 비교자의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 가변 스팬 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 읽기 전용 스팬 |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | 요소 비교에 사용할 동등 비교자 |

### 반환 값

두 스팬 시작 부분에서 일치하는 요소의 수

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) 함수

사용자 정의 동등 비교자를 사용하여 두 가변 스팬 사이의 공통 접두사의 길이를 찾습니다.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬의 요소 유형 |
| TEqualityComparer | 동등 비교자의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 첫 번째 가변 스팬 |
| other | const [Span](../../system/span/)\<T\>\& | 두 번째 가변 스팬 |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | 요소 비교에 사용할 동등 비교자 |

### 반환 값

두 스팬 시작 부분에서 일치하는 요소의 수

## 참고

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)