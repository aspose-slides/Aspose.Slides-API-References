---
title: LINQ_Select()
second_title: Aspose.Slides for C++ API 参考
description: 转换序列的元素。
type: docs
weight: 248
url: /zh/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) method


转换序列的元素。

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| ResultType | selector 返回的值的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | 转换函数。 |

### 返回值

一个 [IEnumerable](../)，其中包含 **selector** 函数返回的元素。

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) method


通过结合元素的索引，将序列的每个元素转换为新形式。

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| ResultType | selector 返回的值的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | 转换函数。 |

### 返回值

一个 [IEnumerable](../)，其中包含 **selector** 函数返回的元素。

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IEnumerable](../)
* 类 [Func](../../../system/func/)
* 命名空间 [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)