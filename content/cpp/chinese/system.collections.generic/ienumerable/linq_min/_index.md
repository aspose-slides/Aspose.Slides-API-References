---
title: LINQ_Min()
second_title: Aspose.Slides for C++ API 参考
description: 对通用序列的每个元素调用转换函数，并返回最小的结果值。
type: docs
weight: 326
url: /zh/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) 方法


对通用序列的每个元素调用转换函数，并返回最小的结果值。

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| ResultType | selector 返回的值的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | 对每个元素应用的转换函数。 |

### 返回值

序列中的最小值。

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) 方法




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## 另见

* 类 [Func](../../../system/func/)
* 类 [IEnumerable](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)