---
title: CopyTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 배열의 모든 요소를 지정된 대상 배열에 복사합니다. 요소는 arrayIndex 인수로 지정된 인덱스부터 대상 배열에 삽입됩니다.
type: docs
weight: 118
url: /ko/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) 메서드

현재 배열의 모든 요소를 지정된 대상 배열에 복사합니다. 요소는 arrayIndex 인수로 지정된 인덱스부터 대상 배열에 삽입됩니다.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | 대상 배열 |
| arrayIndex | int | [Index](../../index/) 로 대상 배열에 복사된 항목을 삽입하기 시작하는 인덱스 |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const 메서드

현재 배열의 모든 요소를 지정된 대상 배열에 복사합니다. 요소는 dstIndex 인수로 지정된 인덱스부터 대상 배열에 삽입됩니다.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| DstType | 대상 배열의 요소 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 대상 배열 |
| dstIndex | **int64_t** | [Index](../../index/) 로 대상 배열에 복사된 항목을 삽입하기 시작하는 인덱스 |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const 메서드

현재 배열의 모든 요소를 지정된 대상 배열 보기로 복사합니다. 요소는 dstIndex 인수로 지정된 인덱스부터 대상 배열 보기에 삽입됩니다.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| DstType | 대상 배열 보기의 요소 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | 대상 배열 보기 |
| dstIndex | **int64_t** | [Index](../../index/) 로 대상 배열 보기에서 복사된 항목을 삽입하기 시작하는 인덱스 |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const 메서드

현재 배열에서 지정된 위치부터 지정된 개수만큼의 요소를 대상 배열에 복사합니다. 요소는 dstIndex 인수로 지정된 인덱스부터 대상 배열에 삽입됩니다.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| DstType | 대상 배열의 요소 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 대상 배열 |
| srcIndex | **int64_t** | [Index](../../index/) 로 소스 배열에서 복사 작업을 시작하는 인덱스 |
| dstIndex | **int64_t** | [Index](../../index/) 로 대상 배열에 복사된 항목을 삽입하기 시작하는 인덱스 |
| count | **int64_t** | 복사할 요소 개수 |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const 메서드

현재 배열에서 지정된 위치부터 지정된 개수만큼의 요소를 대상 배열 보기로 복사합니다. 요소는 dstIndex 인수로 지정된 인덱스부터 대상 배열 보기에 삽입됩니다.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| DstType | 대상 배열 보기의 요소 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | 대상 배열 보기 |
| srcIndex | **int64_t** | [Index](../../index/) 로 소스 배열에서 복사 작업을 시작하는 인덱스 |
| dstIndex | **int64_t** | [Index](../../index/) 로 대상 배열 보기에서 복사된 항목을 삽입하기 시작하는 인덱스 |
| count | **int64_t** | 복사할 요소 개수 |

## 참고

* Typedef [ArrayPtr](../../arrayptr/)
* 클래스 [Array](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)