---
title: SequenceEqual()
second_title: Aspose.Slides for C++ API 참조
description: 두 ReadOnlySpans가 동일한 순서로 동일한 요소를 포함하는지 확인합니다.
type: docs
weight: 326
url: /ko/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

두 ReadOnlySpans가 동일한 순서로 동일한 요소를 포함하는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 비교할 첫 번째 span |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 비교할 두 번째 span |

### 반환값

스팬의 길이가 같고 모든 요소가 동일하면 true, 그렇지 않으면 false

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 함수

a [Span](../../system/span/)와 [ReadOnlySpan](../../system/readonlyspan/)가 동일한 순서로 동일한 요소를 포함하는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 비교할 [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 비교할 [ReadOnlySpan](../../system/readonlyspan/) |

### 반환값

스팬의 길이가 같고 모든 요소가 동일하면 true, 그렇지 않으면 false

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) 함수

두 ReadOnlySpans가 사용자 지정 비교자를 사용하여 동일한 요소를 포함하는지 확인합니다.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 유형 |
| TComparer | 비교자 객체의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 비교할 첫 번째 span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 비교할 두 번째 span |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 요소 비교를 위한 비교자 객체에 대한 스마트 포인터 |

### 반환값

스팬의 길이가 같고 비교자가 모든 요소를 동일하다고 판단하면 true, 그렇지 않으면 false

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) 함수

[Span](../../system/span/)와 [ReadOnlySpan](../../system/readonlyspan/)가 사용자 지정 비교자를 사용하여 동일한 요소를 포함하는지 확인합니다.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 유형 |
| TComparer | 비교자 객체의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 비교할 [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 비교할 [ReadOnlySpan](../../system/readonlyspan/) |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 요소 비교를 위한 비교자 객체에 대한 스마트 포인터 |

### 반환값

스팬의 길이가 같고 비교자가 모든 요소를 동일하다고 판단하면 true, 그렇지 않으면 false

## 참조

* Typedef [SharedPtr](../../system/sharedptr/)
* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)