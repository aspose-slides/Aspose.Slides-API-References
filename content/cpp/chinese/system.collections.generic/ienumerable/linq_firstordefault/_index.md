---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides for C++ API 参考
description: 返回序列的第一个元素，如果序列为空则返回默认值。
type: docs
weight: 66
url: /zh/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() 方法

返回序列的第一个元素，如果序列为空则返回默认值。

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```

### 返回值

序列中的第一个元素；如果序列为空则返回默认构造的值。

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) 方法

返回满足条件的序列中的第一个元素，如果未找到此类元素则返回默认值。

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | 用于测试每个元素是否满足条件的函数。 |

### 返回值

如果 source 为空或没有元素通过 predicate 指定的测试，则返回 default(T)；否则返回 source 中第一个通过该测试的元素。

## 另见

* 类 [IEnumerable](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)