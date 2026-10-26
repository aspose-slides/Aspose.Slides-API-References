---
title: AsSpan()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 배열에서 Span을 생성합니다.
type: docs
weight: 1
url: /ko/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) 함수

배열에서 Span을 생성합니다.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 배열의 요소 유형입니다. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | 원본 배열입니다. |
| start | **int32_t** | 배열에서 시작 인덱스입니다. |
| length | **int32_t** | Span의 길이입니다. |

### 반환 값

배열의 지정된 부분을 포함하는 Span<T>.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) 함수

문자열에서 읽기 전용 Span을 생성합니다.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | 원본 문자열입니다. |
| start | **int32_t** | 문자열에서 시작 인덱스입니다. |
| length | **int32_t** | Span의 길이입니다. |

### 반환 값

문자열의 지정된 부분을 포함하는 ReadOnlySpan<char16_t>.

## 또 보기

* 타입정의 [ArrayPtr](../../system/arrayptr/)
* 클래스 [Span](../../system/span/)
* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [String](../../system/string/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)