---
title: LINQ_Max()
second_title: Aspose.Slides for C++ API 参考
description: 对通用序列的每个元素调用转换函数并返回最大的结果值。
type: docs
weight: 339
url: /zh/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) 方法

对通用序列的每个元素调用转换函数并返回最大的结果值。

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| ResultType | selector 返回的值的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | 要应用于每个元素的转换函数。 |

### 返回值

序列中的最大值。

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) 方法




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## 另见

* 类 [Func](../../../system/func/)
* 类 [IEnumerable](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)