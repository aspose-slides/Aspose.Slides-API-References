---
title: LINQ_All()
second_title: Aspose.Slides C++ API 参考
description: 确定序列的所有元素是否满足条件。
type: docs
weight: 144
url: /zh/system.collections.generic/ienumerable/linq_all/
---
## IEnumerable::LINQ_All(std::function\<bool(T)>) 方法

确定序列的所有元素是否满足条件。

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_All(std::function<bool(T)> predicate)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | 用于测试每个元素是否满足条件的函数。 |

### 返回值

如果源序列的每个元素都通过指定谓词的测试，或者序列为空，则返回 true；否则返回 false。

## 另见

* 类 [IEnumerable](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)