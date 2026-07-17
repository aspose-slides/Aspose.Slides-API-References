---
title: LINQ_Count()
second_title: Aspose.Slides for C++ API 参考
description: 返回序列中元素的数量（通过直接计数计算）。
type: docs
weight: 118
url: /zh/system.collections.generic/ienumerable/linq_count/
---
## IEnumerable::LINQ_Count() 方法

返回序列中元素的数量（通过直接计数计算）。

```cpp
int System::Collections::Generic::IEnumerable<T>::LINQ_Count()
```

### 返回值

序列中元素的数量。

## IEnumerable::LINQ_Count(const Func\<T, bool\>\&) 方法

返回满足指定条件的序列中元素的数量。

```cpp
int System::Collections::Generic::IEnumerable<T>::LINQ_Count(const Func<T, bool> &predicate)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| predicate | const [Func](../../../system/func/)\<T, **bool**\>\& | 用于测试每个元素是否满足条件的函数。 |

### 返回值

满足指定条件的序列中元素的数量。

## 另请参见

* 类 [IEnumerable](../)
* 类 [Func](../../../system/func/)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)