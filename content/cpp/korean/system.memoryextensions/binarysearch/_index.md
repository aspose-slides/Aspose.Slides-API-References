---
title: BinarySearch()
second_title: C++용 Aspose.Slides API 참조
description: 정렬된 스팬에서 이진 검색을 수행합니다.
type: docs
weight: 14
url: /ko/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) function


정렬된 스팬에서 이진 검색을 수행합니다.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 유형 |
| TComparable | 비교 가능한 값의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 정렬된 스팬 |
| comparable | const TComparable\& | 검색할 값 |

### 반환 값

[Index](../../system/index/) of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) function


사용자 지정 비교자를 사용하여 정렬된 스팬에서 이진 검색을 수행합니다.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 유형 |
| TComparer | 비교자의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 정렬된 스팬 |
| value | const T\& | 검색할 값 |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 비교에 사용할 comparer |

### 반환 값

[Index](../../system/index/) of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) function


변경 가능한 정렬된 스팬에서 이진 검색을 수행합니다.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 유형 |
| TComparable | 비교 가능한 값의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 정렬된 스팬 |
| comparable | const TComparable\& | 검색할 값 |

### 반환 값

[Index](../../system/index/) of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) function


사용자 지정 비교자를 사용하여 변경 가능한 정렬된 스팬에서 이진 검색을 수행합니다.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 포함된 요소의 유형 |
| TComparer | 비교자의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 정렬된 스팬 |
| value | const T\& | 검색할 값 |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 비교에 사용할 comparer |

### 반환 값

[Index](../../system/index/) of the found element, or bitwise complement of the insertion point if not found

## 관련 항목

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)