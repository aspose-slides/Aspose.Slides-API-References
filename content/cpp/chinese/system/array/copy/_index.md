---
title: Copy()
second_title: Aspose.Slides for C++ API 参考
description: 将指定数量的元素从源数组复制到目标数组。
type: docs
weight: 729
url: /zh/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) 方法


将指定数量的元素从源数组复制到目标数组。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 源数组 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目标数组 |
| count | **int64_t** | 要复制的元素数量 |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) 方法


将指定数量的元素从源数组视图复制到目标数组。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | 源数组视图 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目标数组 |
| count | **int64_t** | 要复制的元素数量 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) 方法


将指定数量的元素从源数组复制到目标数组视图。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 源数组 |
| dstArray | System::Details::ArrayView\<DstType\> | 目标数组视图 |
| count | **int64_t** | 要复制的元素数量 |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) 方法


将指定数量的元素从源数组视图复制到目标数组视图。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | 源数组视图 |
| dstArray | System::Details::ArrayView\<DstType\> | 目标数组视图 |
| count | **int64_t** | 要复制的元素数量 |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) 方法


将指定数量的元素从栈上的源数组复制到目标数组。

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | 栈上的源数组 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目标数组 |
| count | **int64_t** | 要复制的元素数量 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) 方法


将指定数量的元素从源数组复制到栈上的目标数组。

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 源数组 |
| dstArray | System::Details::StackArray\<DstType, N\>\& | 栈上的目标数组 |
| count | **int64_t** | 要复制的元素数量 |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) 方法


将指定数量的元素从栈上的源数组复制到栈上的目标数组。

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | 栈上的源数组 |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | 栈上的目标数组 |
| count | **int64_t** | 要复制的元素数量 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) 方法


将源数组中从指定索引开始的若干元素复制到目标数组的指定位置。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| SrcType | 源数组中元素的类型 |
| DstType | 目标数组中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 源数组 |
| srcIndex | **int64_t** | 源数组中指定要复制范围起始的索引 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目标数组 |
| dstIndex | **int64_t** | 目标数组中开始插入复制项的索引 |
| count | **int64_t** | 要复制的元素数量 |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) 方法


将源数组视图中从指定索引开始的若干元素复制到目标数组的指定位置。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| SrcType | 源数组视图中元素的类型 |
| DstType | 目标数组中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | 源数组视图 |
| srcIndex | **int64_t** | 源数组视图中指定要复制范围起始的索引 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目标数组 |
| dstIndex | **int64_t** | 目标数组中开始插入复制项的索引 |
| count | **int64_t** | 要复制的元素数量 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) 方法


将源数组中从指定索引开始的若干元素复制到目标数组视图的指定位置。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| SrcType | 源数组中元素的类型 |
| DstType | 目标数组视图中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 源数组 |
| srcIndex | **int64_t** | 源数组中指定要复制范围起始的索引 |
| dstArray | System::Details::ArrayView\<DstType\> | 目标数组视图 |
| dstIndex | **int64_t** | 目标数组视图中开始插入复制项的索引 |
| count | **int64_t** | 要复制的元素数量 |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) 方法


将源数组视图中从指定索引开始的若干元素复制到目标数组视图的指定位置。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| SrcType | 源数组视图中元素的类型 |
| DstType | 目标数组视图中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | 源数组视图 |
| srcIndex | **int64_t** | 源数组视图中指定要复制范围起始的索引 |
| dstArray | System::Details::ArrayView\<DstType\> | 目标数组视图 |
| dstIndex | **int64_t** | 目标数组视图中开始插入复制项的索引 |
| count | **int64_t** | 要复制的元素数量 |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) 方法


将栈上的源数组中从指定索引开始的若干元素复制到目标数组的指定位置。

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| SrcType | 栈上源数组中元素的类型 |
| DstType | 目标数组中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | 栈上的源数组 |
| srcIndex | **int64_t** | 栈上源数组中指定要复制范围起始的索引 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目标数组 |
| dstIndex | **int64_t** | 目标数组中开始插入复制项的索引 |
| count | **int64_t** | 要复制的元素数量 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) 方法


将源数组中从指定索引开始的若干元素复制到栈上的目标数组的指定位置。

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| SrcType | 源数组中元素的类型 |
| DstType | 栈上目标数组中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 源数组 |
| srcIndex | **int64_t** | 源数组中指定要复制范围起始的索引 |
| dstArray | System::Details::StackArray\<DstType, N\>\& | 栈上的目标数组 |
| dstIndex | **int64_t** | 栈上目标数组中开始插入复制项的索引 |
| count | **int64_t** | 要复制的元素数量 |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) 方法


将栈上的源数组中从指定索引开始的若干元素复制到栈上的目标数组的指定位置。

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| SrcType | 栈上源数组中元素的类型 |
| DstType | 栈上目标数组中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | 栈上的源数组 |
| srcIndex | **int64_t** | 栈上源数组中指定要复制范围起始的索引 |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | 栈上的目标数组 |
| dstIndex | **int64_t** | 栈上目标数组中开始插入复制项的索引 |
| count | **int64_t** | 要复制的元素数量 |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) 方法


将源数组视图中从指定索引开始的若干元素复制到栈上的目标数组的指定位置。

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| SrcType | 栈上源数组中元素的类型 |
| DstType | 栈上目标数组中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | 源数组视图 |
| srcIndex | **int64_t** | 源数组视图中指定要复制范围起始的索引 |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | 栈上的目标数组 |
| dstIndex | **int64_t** | 栈上目标数组中开始插入复制项的索引 |
| count | **int64_t** | 要复制的元素数量 |

## 另见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [Array](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)