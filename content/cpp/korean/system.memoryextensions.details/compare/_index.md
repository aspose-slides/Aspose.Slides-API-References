---
title: Compare()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 두 스마트 포인터를 비교합니다.
type: docs
weight: 1
url: /ko/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) 함수

두 스마트 포인터를 비교합니다.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 첫 번째 스마트 포인터의 유형 |
| U | 두 번째 스마트 포인터의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | 첫 번째 스마트 포인터 |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | 두 번째 스마트 포인터 |

### 반환 값

[Comparison](../../system/comparison/) 결과 (0이면 동일, -1이면 a < b, 1이면 a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) 함수

두 산술 값을 비교합니다.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 산술 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | const T\& | 첫 번째 값 |
| b | const T\& | 두 번째 값 |

### 반환 값

[Comparison](../../system/comparison/) 결과 (0이면 동일, -1이면 a < b, 1이면 a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) 함수

스마트 포인터와 값을 비교합니다.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스마트 포인터가 가리키는 유형 |
| U | 값의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | 스마트 포인터 |
| b | const U\& | 값 |

### 반환 값

[Comparison](../../system/comparison/) 결과 (0이면 동일, -1이면 a < b, 1이면 a > b)

## 참고

* Typedef [SharedPtr](../../system/sharedptr/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)