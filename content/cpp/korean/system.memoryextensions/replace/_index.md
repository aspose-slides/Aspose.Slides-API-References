---
title: Replace()
second_title: Aspose.Slides for C++ API 참조
description: Span에서 값의 모든 발생을 새 값으로 교체합니다.
type: docs
weight: 287
url: /ko/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) 함수

[Span](../../system/span/)에서 값의 모든 발생을 새 값으로 교체합니다.

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 제자리에서 수정할 스팬 |
| oldValue | const T\& | 검색하고 교체할 값 |
| newValue | const T\& | oldValue를 대체할 새 값 |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) 함수

소스에서 대상으로 요소를 복사하면서 지정된 값을 교체합니다.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 복사할 소스 [ReadOnlySpan](../../system/readonlyspan/) |
| destination | [Span](../../system/span/)\<T\>\& | 복사할 대상 [Span](../../system/span/) |
| oldValue | const T\& | 복사 중에 검색하고 교체할 값 |
| newValue | const T\& | oldValue를 대체할 새 값 |

## 참고

* 클래스 [Span](../../system/span/)
* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)