---
title: Copy()
second_title: Aspose.Slides for C++ API 參考
description: 將指定數量的元素從來源陣列複製到目標陣列。
type: docs
weight: 729
url: /zh-hant/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) 方法

將指定數量的元素從來源陣列複製到目標陣列。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 來源陣列 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目標陣列 |
| count | **int64_t** | 要複製的元素數量 |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) 方法

將指定數量的元素從來源陣列視圖複製到目標陣列。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | 來源陣列視圖 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目標陣列 |
| count | **int64_t** | 要複製的元素數量 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) 方法

將指定數量的元素從來源陣列複製到目標陣列視圖。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 來源陣列 |
| dstArray | System::Details::ArrayView\<DstType\> | 目標陣列視圖 |
| count | **int64_t** | 要複製的元素數量 |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) 方法

將指定數量的元素從來源陣列視圖複製到目標陣列視圖。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | 來源陣列視圖 |
| dstArray | System::Details::ArrayView\<DstType\> | 目標陣列視圖 |
| count | **int64_t** | 要複製的元素數量 |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) 方法

將指定數量的元素從堆疊上的來源陣列複製到目標陣列。

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | 堆疊上的來源陣列 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目標陣列 |
| count | **int64_t** | 要複製的元素數量 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) 方法

將指定數量的元素從來源陣列複製到堆疊上的目標陣列。

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 來源陣列 |
| dstArray | System::Details::StackArray\<DstType, N\>\& | 堆疊上的目標陣列 |
| count | **int64_t** | 要複製的元素數量 |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) 方法

將指定數量的元素從堆疊上的來源陣列複製到堆疊上的目標陣列。

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | 堆疊上的來源陣列 |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | 堆疊上的目標陣列 |
| count | **int64_t** | 要複製的元素數量 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) 方法

將來源陣列自指定索引開始的指定數量元素複製到目標陣列的指定位置。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| SrcType | 來源陣列中元素的類型 |
| DstType | 目標陣列中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 來源陣列 |
| srcIndex | **int64_t** | [Index](../../index/) 在來源陣列中，指定要複製之範圍的開始位置 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目標陣列 |
| dstIndex | **int64_t** | [Index](../../index/) 在目標陣列中，開始插入複製項目的位置 |
| count | **int64_t** | 要複製的元素數量 |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) 方法

將來源陣列視圖自指定索引開始的指定數量元素複製到目標陣列的指定位置。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| SrcType | 來源陣列視圖中元素的類型 |
| DstType | 目標陣列中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | 來源陣列視圖 |
| srcIndex | **int64_t** | [Index](../../index/) 在來源陣列視圖中，指定要複製之範圍的開始位置 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目標陣列 |
| dstIndex | **int64_t** | [Index](../../index/) 在目標陣列中，開始插入複製項目的位置 |
| count | **int64_t** | 要複製的元素數量 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) 方法

將來源陣列自指定索引開始的指定數量元素複製到目標陣列視圖的指定位置。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| SrcType | 來源陣列中元素的類型 |
| DstType | 目標陣列視圖中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 來源陣列 |
| srcIndex | **int64_t** | [Index](../../index/) 在來源陣列中，指定要複製之範圍的開始位置 |
| dstArray | System::Details::ArrayView\<DstType\> | 目標陣列視圖 |
| dstIndex | **int64_t** | [Index](../../index/) 在目標陣列視圖中，開始插入複製項目的位置 |
| count | **int64_t** | 要複製的元素數量 |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) 方法

將來源陣列視圖自指定索引開始的指定數量元素複製到目標陣列視圖的指定位置。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| SrcType | 來源陣列視圖中元素的類型 |
| DstType | 目標陣列視圖中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | 來源陣列視圖 |
| srcIndex | **int64_t** | [Index](../../index/) 在來源陣列視圖中，指定要複製之範圍的開始位置 |
| dstArray | System::Details::ArrayView\<DstType\> | 目標陣列視圖 |
| dstIndex | **int64_t** | [Index](../../index/) 在目標陣列視圖中，開始插入複製項目的位置 |
| count | **int64_t** | 要複製的元素數量 |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) 方法

將堆疊上的來源陣列自指定索引開始的指定數量元素複製到目標陣列的指定位置。

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| SrcType | 堆疊上的來源陣列中元素的類型 |
| DstType | 目標陣列中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | 堆疊上的來源陣列 |
| srcIndex | **int64_t** | [Index](../../index/) 在堆疊上的來源陣列中，指定要複製之範圍的開始位置 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目標陣列 |
| dstIndex | **int64_t** | [Index](../../index/) 在目標陣列中，開始插入複製項目的位置 |
| count | **int64_t** | 要複製的元素數量 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) 方法

將來源陣列自指定索引開始的指定數量元素複製到堆疊上的目標陣列的指定位置。

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| SrcType | 來源陣列中元素的類型 |
| DstType | 堆疊上的目標陣列中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 來源陣列 |
| srcIndex | **int64_t** | [Index](../../index/) 在來源陣列中，指定要複製之範圍的開始位置 |
| dstArray | System::Details::StackArray\<DstType, N\>\& | 堆疊上的目標陣列 |
| dstIndex | **int64_t** | [Index](../../index/) 在堆疊上的目標陣列中，開始插入複製項目的位置 |
| count | **int64_t** | 要複製的元素數量 |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) 方法

將堆疊上的來源陣列自指定索引開始的指定數量元素複製到堆疊上的目標陣列的指定位置。

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| SrcType | 堆疊上的來源陣列中元素的類型 |
| DstType | 堆疊上的目標陣列中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | 堆疊上的來源陣列 |
| srcIndex | **int64_t** | [Index](../../index/) 在堆疊上的來源陣列中，指定要複製之範圍的開始位置 |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | 堆疊上的目標陣列 |
| dstIndex | **int64_t** | [Index](../../index/) 在堆疊上的目標陣列中，開始插入複製項目的位置 |
| count | **int64_t** | 要複製的元素數量 |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) 方法

將來源陣列視圖自指定索引開始的指定數量元素複製到堆疊上的目標陣列的指定位置。

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| SrcType | 堆疊上的來源陣列中元素的類型 |
| DstType | 堆疊上的目標陣列中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | 來源陣列視圖 |
| srcIndex | **int64_t** | [Index](../../index/) 在來源陣列視圖中，指定要複製之範圍的開始位置 |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | 堆疊上的目標陣列 |
| dstIndex | **int64_t** | [Index](../../index/) 在堆疊上的目標陣列中，開始插入複製項目的位置 |
| count | **int64_t** | 要複製的元素數量 |

## 參見

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)