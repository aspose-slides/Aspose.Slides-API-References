---
title: ContainsAnyInRange()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 읽기 전용 스팬에 지정된 범위 내에 요소가 포함되어 있는지 확인합니다.
type: docs
weight: 92
url: /ko/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

읽기 전용 스팬에 지정된 범위 내의 요소가 포함되어 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬의 요소 타입(비교 가능해야 함) |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 스팬 |
| lowInclusive | const T\& | 하한 (포함) |
| highInclusive | const T\& | 상한 (포함) |

### 반환값

범위 내에 요소가 하나라도 발견되면 true, 그렇지 않으면 false

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) function

가변 스팬에 지정된 범위 내의 요소가 포함되어 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬의 요소 타입(비교 가능해야 함) |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 가변 스팬 |
| lowInclusive | const T\& | 하한 (포함) |
| highInclusive | const T\& | 상한 (포함) |

### 반환값

범위 내에 요소가 하나라도 발견되면 true, 그렇지 않으면 false

## 참고

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)