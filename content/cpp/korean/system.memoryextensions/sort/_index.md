---
title: Sort()
second_title: Aspose.Slides for C++ API 참조
description: Span을 사용자 지정 비교기를 사용하여 정렬합니다.
type: docs
weight: 339
url: /ko/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) 함수

[Span](../../system/span/)를 사용자 지정 비교기를 사용하여 정렬합니다.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소들의 유형 |
| TComparer | 비교기 객체의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 정렬할 스팬 |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 요소 비교를 위한 비교기 객체에 대한 스마트 포인터 |

## System::MemoryExtensions::Sort(Span\<T\>\&) 함수

[Span](../../system/span/)를 기본 비교를 사용하여 정렬합니다.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소들의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 정렬할 스팬 |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) 함수

키-값 쌍을 사용자 지정 비교기를 사용하여 정렬합니다 (키와 값이 함께 정렬됩니다)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TKey | 키의 유형 |
| TValue | 값의 유형 |
| TComparer | 비교기 객체의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 정렬할 키들의 스팬 |
| values | [Span](../../system/span/)\<TValue\>\& | 키와의 일치를 유지하면서 정렬할 값들의 스팬 |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 키 비교를 위한 비교기 객체에 대한 스마트 포인터 |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) 함수

키-값 쌍을 비교 대리자를 사용하여 정렬합니다.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TKey | 키의 유형 |
| TValue | 값의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 정렬할 키들의 스팬 |
| values | [Span](../../system/span/)\<TValue\>\& | 정렬할 값들의 스팬 |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) 키 비교를 위한 대리자 |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) 함수

키-값 쌍을 기본 비교를 사용하여 정렬합니다.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TKey | 키의 유형 |
| TValue | 값의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 정렬할 키들의 스팬 |
| values | [Span](../../system/span/)\<TValue\>\& | 정렬할 값들의 스팬 |

## 참고

* 타입정의 [SharedPtr](../../system/sharedptr/)
* 클래스 [Span](../../system/span/)
* 클래스 [Comparison](../../system/comparison/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)