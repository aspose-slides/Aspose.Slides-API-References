---
title: CopyTo()
second_title: Aspose.Slides for C++ API 參考手冊
description: 將目前陣列的所有元素複製到指定的目標陣列。元素會在目標陣列中從 arrayIndex 參數指定的索引開始插入。
type: docs
weight: 118
url: /zh-hant/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) 方法

將目前陣列的所有元素複製到指定的目標陣列。元素會在目標陣列中從 arrayIndex 參數指定的索引開始插入。

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | 目標陣列 |
| arrayIndex | int | [Index](../../index/) 在目標陣列中開始插入複製項目的索引 |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const 方法

將目前陣列的所有元素複製到指定的目標陣列。元素會在目標陣列中從 dstIndex 參數指定的索引開始插入。

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| DstType | 目標陣列中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目標陣列 |
| dstIndex | **int64_t** | [Index](../../index/) 在目標陣列中開始插入複製項目的索引 |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const 方法

將目前陣列的所有元素複製到指定的目標陣列視圖。元素會在目標陣列視圖中從 dstIndex 參數指定的索引開始插入。

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| DstType | 目標陣列視圖中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | 目標陣列視圖 |
| dstIndex | **int64_t** | [Index](../../index/) 在目標陣列視圖中開始插入複製項目的索引 |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const 方法

將目前陣列中自指定位置起的指定數量元素複製到指定的目標陣列。元素會在目標陣列中從 dstIndex 參數指定的索引開始插入。

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| DstType | 目標陣列中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目標陣列 |
| srcIndex | **int64_t** | [Index](../../index/) 在來源陣列中開始複製項目的索引 |
| dstIndex | **int64_t** | [Index](../../index/) 在目標陣列中開始插入複製項目的索引 |
| count | **int64_t** | 要複製的元素數量 |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const 方法

將目前陣列中自指定位置起的指定數量元素複製到指定的目標陣列視圖。元素會在目標陣列視圖中從 dstIndex 參數指定的索引開始插入。

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| DstType | 目標陣列視圖中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | 目標陣列視圖 |
| srcIndex | **int64_t** | [Index](../../index/) 在來源陣列中開始複製項目的索引 |
| dstIndex | **int64_t** | [Index](../../index/) 在目標陣列視圖中開始插入複製項目的索引 |
| count | **int64_t** | 要複製的元素數量 |

## 參見

* 型別別名 [ArrayPtr](../../arrayptr/)
* 類別 [Array](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)