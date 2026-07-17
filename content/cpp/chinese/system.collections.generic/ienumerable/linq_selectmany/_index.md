---
title: LINQ_SelectMany()
second_title: Aspose.Slides C++ API 参考
description: 对序列中的每个元素进行投影，并将产生的序列合并为一个序列。
type: docs
weight: 300
url: /zh/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) method

对序列中的每个元素进行投影，并将产生的序列合并为一个序列。

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| ResultType | 由 **selector** 返回的值的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | 一个转换函数。 |

### 返回值

一个 [IEnumerable](../)，其中包含对输入序列的每个元素调用一对多投影函数的结果。

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) method

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IEnumerable](../)
* 类 [Func](../../../system/func/)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)