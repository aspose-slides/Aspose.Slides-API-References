---
title: ContainsAnyExceptInRange()
second_title: Aspose.Slides for C++ API 참조
description: 읽기 전용 스팬에 지정된 범위 밖의 요소가 있는지 확인합니다.
type: docs
weight: 79
url: /ko/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 함수


읽기 전용 스팬에 지정된 범위 밖의 요소가 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 유형(비교 가능해야 함) |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 스팬 |
| lowInclusive | const T\& | 하한(포함) |
| highInclusive | const T\& | 상한(포함) |

### 반환값

범위 외의 요소가 발견되면 true, 그렇지 않으면 false

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) 함수


읽기/쓰기 가능한 스팬에 지정된 범위 밖의 요소가 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 유형(비교 가능해야 함) |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 변경 가능한 스팬 |
| lowInclusive | const T\& | 하한(포함) |
| highInclusive | const T\& | 상한(포함) |

### 반환값

범위 외의 요소가 발견되면 true, 그렇지 않으면 false

## 참고

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)