---
title: LINQ_Where()
second_title: Aspose.Slides C++ API 参考
description: 根据指定的谓词过滤序列。
type: docs
weight: 170
url: /zh/system.collections.generic/ienumerable/linq_where/
---
## IEnumerable::LINQ_Where(std::function\<bool(T)>) method


根据指定的谓词过滤序列。

```cpp
SharedPtr<IEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_Where(std::function<bool(T)> predicate)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | 一个针对每个元素进行某种条件测试的函数。 |

### 返回值

一个包含过滤后元素的[IEnumerable](../)。

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IEnumerable](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)