---
title: EndsWith()
second_title: Aspose.Slides for C++ API 참조
description: ReadOnlySpan<T>가 단일 값으로 끝나는지 확인합니다.
type: docs
weight: 131
url: /ko/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) 함수

ReadOnlySpan<T>가 단일 값으로 끝나는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 각 span에 있는 요소들의 타입 |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 확인할 span |
| value | const T\& | span의 끝에서 확인할 값 |

### 반환 값

span이 해당 값으로 끝나면 true, 그렇지 않으면 false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

ReadOnlySpan<T>가 다른 ReadOnlySpan<T>로 끝나는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 각 span에 있는 요소들의 타입 |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 확인할 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 대상 span의 끝에서 확인할 span |

### 반환 값

span이 해당 값 span으로 끝나면 true, 그렇지 않으면 false

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

Span<T>가 ReadOnlySpan<T>로 끝나는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 각 span에 있는 요소들의 타입 |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 확인할 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 대상 span의 끝에서 확인할 span |

### 반환 값

span이 해당 값 span으로 끝나면 true, 그렇지 않으면 false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) 함수

ReadOnlySpan<T>가 Span<T>로 끝나는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 각 span에 있는 요소들의 타입 |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 확인할 span |
| value | const [Span](../../system/span/)\<T\>\& | 대상 span의 끝에서 확인할 span |

### 반환 값

span이 해당 값 span으로 끝나면 true, 그렇지 않으면 false

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) 함수

Span<T>가 다른 Span<T>로 끝나는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 각 span에 있는 요소들의 타입 |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 확인할 span |
| value | const [Span](../../system/span/)\<T\>\& | 대상 span의 끝에서 확인할 span |

### 반환 값

span이 해당 값 span으로 끝나면 true, 그렇지 않으면 false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 함수

ReadOnlySpan<char16_t>가 StringComparison을 사용하여 지정된 값으로 끝나는지 확인합니다.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 확인할 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | span의 끝에서 확인할 값 |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 사용할 문자열 비교 유형 |

### 반환 값

span이 해당 값으로 끝나면 true, 그렇지 않으면 false

## 참조

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)