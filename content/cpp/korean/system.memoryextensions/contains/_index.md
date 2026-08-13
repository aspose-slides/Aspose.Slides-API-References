---
title: Contains()
second_title: Aspose.Slides for C++ API 참조
description: 읽기 전용 Span에 특정 값이 포함되어 있는지 확인합니다.
type: docs
weight: 40
url: /ko/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) function

읽기 전용 Span에 특정 값이 포함되어 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Span에 포함된 요소의 형식 |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 Span |
| value | const T\& | 검색할 값 |

### 반환 값

값이 Span에 있으면 true, 그렇지 않으면 false

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) function

가변 Span에 특정 값이 포함되어 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Span에 포함된 요소의 형식 |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 가변 Span |
| value | const T\& | 검색할 값 |

### 반환 값

값이 Span에 있으면 true, 그렇지 않으면 false

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

문자 Span이 지정된 비교 규칙을 사용하여 다른 문자 Span을 포함하고 있는지 확인합니다.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 검색할 Span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 검색할 Span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 수행할 문자열 비교 유형 |

### 반환 값

값이 Span에 있으면 true, 그렇지 않으면 false

## 참고

* 열거형 [StringComparison](../../system/stringcomparison/)
* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)