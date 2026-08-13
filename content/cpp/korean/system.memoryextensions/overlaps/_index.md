---
title: Overlaps()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 두 ReadOnlySpan이 메모리에서 오프셋을 계산하지 않고 겹치는지 확인합니다.
type: docs
weight: 274
url: /ko/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

두 ReadOnlySpan이 메모리에서 겹치는지 오프셋을 계산하지 않고 결정합니다.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 첫 번째 span이 겹치는지 확인 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 두 번째 span이 겹치는지 확인 |

### 반환값

스팬이 공통 메모리 위치를 공유하면 true, 그렇지 않으면 false

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

메모리에서 [Span](../../system/span/)와 [ReadOnlySpan](../../system/readonlyspan/)가 오프셋을 계산하지 않고 겹치는지 결정합니다.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/)가 겹치는지 확인 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/)가 겹치는지 확인 |

### 반환값

스팬이 공통 메모리 위치를 공유하면 true, 그렇지 않으면 false

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) 함수

두 ReadOnlySpan이 메모리에서 겹치는지 확인하고 오프셋을 계산합니다.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 첫 번째 span이 겹치는지 확인 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 두 번째 span이 겹치는지 확인 |
| elementOffset | **int32_t**\& | 스팬이 겹칠 경우 오프셋을 받는 출력 매개변수 |

### 반환값

스팬이 공통 메모리 위치를 공유하면 true, 그렇지 않으면 false

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) 함수

메모리에서 [Span](../../system/span/)와 [ReadOnlySpan](../../system/readonlyspan/)가 겹치는지 확인하고 오프셋을 계산합니다.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/)가 겹치는지 확인 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/)가 겹치는지 확인 |
| elementOffset | **int32_t**\& | 스팬이 겹칠 경우 오프셋을 받는 출력 매개변수 |

### 반환값

스팬이 공통 메모리 위치를 공유하면 true, 그렇지 않으면 false

## 참조

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)