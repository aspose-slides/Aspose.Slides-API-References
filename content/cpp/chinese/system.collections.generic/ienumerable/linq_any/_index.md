---
title: LINQ_Any()
second_title: Aspose.Slides C++ API 参考
description: 确定序列是否包含任何元素。
type: docs
weight: 157
url: /zh/system.collections.generic/ienumerable/linq_any/
---
## IEnumerable::LINQ_Any() 方法


确定序列是否包含任何元素。

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any()
```


### 返回值

true if the source sequence contains any elements; otherwise, false.

## IEnumerable::LINQ_Any(std::function\<bool(T)>) 方法


确定序列的任意元素是否存在或满足条件。

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any(std::function<bool(T)> predicate)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | 用于测试每个元素是否满足条件的函数。 |

### 返回值

true if the source sequence contains any elements; otherwise, false.

## 另请参阅

* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)