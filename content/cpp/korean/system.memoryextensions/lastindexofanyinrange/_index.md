---
title: LastIndexOfAnyInRange()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 범위 내에서 span 안의 요소 중 마지막 발생을 찾습니다.
type: docs
weight: 261
url: /ko/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 함수

지정된 범위 내에서 span 내의 요소 중 마지막 발생을 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span의 요소 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 span |
| lowInclusive | const T\& | 범위의 하한(포함) |
| highInclusive | const T\& | 범위의 상한(포함) |

### 반환 값

범위 내 마지막 요소의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) 함수

지정된 범위 내에서 가변 span의 요소 중 마지막 발생을 찾습니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span의 요소 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 span |
| lowInclusive | const T\& | 범위의 하한(포함) |
| highInclusive | const T\& | 범위의 상한(포함) |

### 반환 값

범위 내 마지막 요소의 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## 또 보기

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)