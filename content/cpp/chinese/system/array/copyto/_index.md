---
title: CopyTo()
second_title: Aspose.Slides for C++ API 参考
description: 将当前数组的所有元素复制到指定的目标数组。元素从由 arrayIndex 参数指定的索引开始插入到目标数组中。
type: docs
weight: 118
url: /zh/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) 方法

复制当前数组的所有元素到指定的目标数组。元素从由 arrayIndex 参数指定的索引开始插入到目标数组中。

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | 目标数组 |
| arrayIndex | int | 在目标数组中开始插入复制项的索引 |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const 方法

复制当前数组的所有元素到指定的目标数组。元素从由 dstIndex 参数指定的索引开始插入到目标数组中。

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| DstType | 目标数组中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目标数组 |
| dstIndex | **int64_t** | 在目标数组中开始插入复制项的索引 |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const 方法

复制当前数组的所有元素到指定的目标数组视图。元素从由 dstIndex 参数指定的索引开始插入到目标数组视图中。

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| DstType | 目标数组视图中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | 目标数组视图 |
| dstIndex | **int64_t** | 在目标数组视图中开始插入复制项的索引 |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const 方法

复制当前数组中从指定位置开始的指定数量的元素到指定的目标数组。元素从由 dstIndex 参数指定的索引开始插入到目标数组中。

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| DstType | 目标数组中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目标数组 |
| srcIndex | **int64_t** | 在源数组中开始复制项的索引 |
| dstIndex | **int64_t** | 在目标数组中开始插入复制项的索引 |
| count | **int64_t** | 要复制的元素数量 |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const 方法

复制当前数组中从指定位置开始的指定数量的元素到指定的目标数组视图。元素从由 dstIndex 参数指定的索引开始插入到目标数组视图中。

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| DstType | 目标数组视图中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | 目标数组视图 |
| srcIndex | **int64_t** | 在源数组中开始复制项的索引 |
| dstIndex | **int64_t** | 在目标数组视图中开始插入复制项的索引 |
| count | **int64_t** | 要复制的元素数量 |

## 另请参见

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)