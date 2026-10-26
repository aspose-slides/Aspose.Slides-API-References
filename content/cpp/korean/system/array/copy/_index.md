---
title: Copy()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 수의 요소를 소스 배열에서 대상 배열로 복사합니다.
type: docs
weight: 729
url: /ko/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) method

지정된 수의 요소를 소스 배열에서 대상 배열로 복사합니다.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 소스 배열 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 대상 배열 |
| count | **int64_t** | 복사할 요소 개수 |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) method

지정된 수의 요소를 소스 배열 뷰에서 대상 배열로 복사합니다.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | 소스 배열 뷰 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 대상 배열 |
| count | **int64_t** | 복사할 요소 개수 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) method

지정된 수의 요소를 소스 배열에서 대상 배열 뷰로 복사합니다.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 소스 배열 |
| dstArray | System::Details::ArrayView\<DstType\> | 대상 배열 뷰 |
| count | **int64_t** | 복사할 요소 개수 |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) method

지정된 수의 요소를 소스 배열 뷰에서 대상 배열 뷰로 복사합니다.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | 소스 배열 뷰 |
| dstArray | System::Details::ArrayView\<DstType\> | 대상 배열 뷰 |
| count | **int64_t** | 복사할 요소 개수 |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) method

지정된 수의 요소를 스택에 있는 소스 배열에서 대상 배열로 복사합니다.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | 스택에 있는 소스 배열 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 대상 배열 |
| count | **int64_t** | 복사할 요소 개수 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) method

지정된 수의 요소를 소스 배열에서 스택에 있는 대상 배열로 복사합니다.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 소스 배열 |
| dstArray | System::Details::StackArray\<DstType, N\>\& | 스택에 있는 대상 배열 |
| count | **int64_t** | 복사할 요소 개수 |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) method

지정된 수의 요소를 스택에 있는 소스 배열에서 스택에 있는 대상 배열로 복사합니다.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | 스택에 있는 소스 배열 |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | 스택에 있는 대상 배열 |
| count | **int64_t** | 복사할 요소 개수 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

지정된 시작 인덱스부터 복사하여 대상 배열의 지정된 위치에 복사합니다.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| SrcType | 소스 배열 요소 유형 |
| DstType | 대상 배열 요소 유형 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 소스 배열 |
| srcIndex | **int64_t** | [Index](../../index/) 소스 배열에서 복사할 항목 범위의 시작을 지정합니다 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 대상 배열 |
| dstIndex | **int64_t** | [Index](../../index/) 대상 배열에서 복사된 항목을 삽입할 시작 위치를 지정합니다 |
| count | **int64_t** | 복사할 요소 개수 |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

지정된 시작 인덱스부터 복사하여 대상 배열에 복사합니다.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| SrcType | 소스 배열 뷰 요소 유형 |
| DstType | 대상 배열 요소 유형 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | 소스 배열 뷰 |
| srcIndex | **int64_t** | [Index](../../index/) 소스 배열 뷰에서 복사할 항목 범위의 시작을 지정합니다 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 대상 배열 |
| dstIndex | **int64_t** | [Index](../../index/) 대상 배열에서 복사된 항목을 삽입할 시작 위치를 지정합니다 |
| count | **int64_t** | 복사할 요소 개수 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method

지정된 시작 인덱스부터 복사하여 대상 배열 뷰에 복사합니다.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| SrcType | 소스 배열 요소 유형 |
| DstType | 대상 배열 뷰 요소 유형 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 소스 배열 |
| srcIndex | **int64_t** | [Index](../../index/) 소스 배열에서 복사할 항목 범위의 시작을 지정합니다 |
| dstArray | System::Details::ArrayView\<DstType\> | 대상 배열 뷰 |
| dstIndex | **int64_t** | [Index](../../index/) 대상 배열 뷰에서 복사된 항목을 삽입할 시작 위치를 지정합니다 |
| count | **int64_t** | 복사할 요소 개수 |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method

지정된 시작 인덱스부터 복사하여 대상 배열 뷰에 복사합니다.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| SrcType | 소스 배열 뷰 요소 유형 |
| DstType | 대상 배열 뷰 요소 유형 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | 소스 배열 뷰 |
| srcIndex | **int64_t** | [Index](../../index/) 소스 배열 뷰에서 복사할 항목 범위의 시작을 지정합니다 |
| dstArray | System::Details::ArrayView\<DstType\> | 대상 배열 뷰 |
| dstIndex | **int64_t** | [Index](../../index/) 대상 배열 뷰에서 복사된 항목을 삽입할 시작 위치를 지정합니다 |
| count | **int64_t** | 복사할 요소 개수 |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

스택에 있는 소스 배열에서 지정된 시작 인덱스부터 복사하여 대상 배열에 복사합니다.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| SrcType | 스택에 있는 소스 배열 요소 유형 |
| DstType | 대상 배열 요소 유형 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | 스택에 있는 소스 배열 |
| srcIndex | **int64_t** | [Index](../../index/) 스택에 있는 소스 배열에서 복사할 항목 범위의 시작을 지정합니다 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 대상 배열 |
| dstIndex | **int64_t** | [Index](../../index/) 대상 배열에서 복사된 항목을 삽입할 시작 위치를 지정합니다 |
| count | **int64_t** | 복사할 요소 개수 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) method

소스 배열에서 지정된 시작 인덱스부터 복사하여 스택에 있는 대상 배열에 복사합니다.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| SrcType | 소스 배열 요소 유형 |
| DstType | 스택에 있는 대상 배열 요소 유형 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 소스 배열 |
| srcIndex | **int64_t** | [Index](../../index/) 소스 배열에서 복사할 항목 범위의 시작을 지정합니다 |
| dstArray | System::Details::StackArray\<DstType, N\>\& | 스택에 있는 대상 배열 |
| dstIndex | **int64_t** | [Index](../../index/) 스택에 있는 대상 배열에서 복사된 항목을 삽입할 시작 위치를 지정합니다 |
| count | **int64_t** | 복사할 요소 개수 |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method

스택에 있는 소스 배열에서 지정된 시작 인덱스부터 복사하여 스택에 있는 대상 배열에 복사합니다.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| SrcType | 스택에 있는 소스 배열 요소 유형 |
| DstType | 스택에 있는 대상 배열 요소 유형 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | 스택에 있는 소스 배열 |
| srcIndex | **int64_t** | [Index](../../index/) 스택에 있는 소스 배열에서 복사할 항목 범위의 시작을 지정합니다 |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | 스택에 있는 대상 배열 |
| dstIndex | **int64_t** | [Index](../../index/) 스택에 있는 대상 배열에서 복사된 항목을 삽입할 시작 위치를 지정합니다 |
| count | **int64_t** | 복사할 요소 개수 |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method

소스 배열 뷰에서 지정된 시작 인덱스부터 복사하여 스택에 있는 대상 배열에 복사합니다.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| SrcType | 스택에 있는 소스 배열 요소 유형 |
| DstType | 스택에 있는 대상 배열 요소 유형 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | 소스 배열 뷰 |
| srcIndex | **int64_t** | [Index](../../index/) 소스 배열 뷰에서 복사할 항목 범위의 시작을 지정합니다 |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | 스택에 있는 대상 배열 |
| dstIndex | **int64_t** | [Index](../../index/) 스택에 있는 대상 배열에서 복사된 항목을 삽입할 시작 위치를 지정합니다 |
| count | **int64_t** | 복사할 요소 개수 |

## See Also

* typedef [ArrayPtr](../../arrayptr/)
* class [Array](../)
* namespace [System](../../)
* library [Aspose.Slides](../../../)