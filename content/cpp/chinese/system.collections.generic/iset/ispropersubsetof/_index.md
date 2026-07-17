---
title: IsProperSubsetOf()
second_title: Aspose.Slides for C++ API 参考
description: 检查当前集合是否为另一个容器的严格子集。
type: docs
weight: 40
url: /zh/system.collections.generic/iset/ispropersubsetof/
---
## ISet::IsProperSubsetOf(IEnumerablePtr) 方法


检查当前集合是否为另一个容器的严格子集。

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsProperSubsetOf(IEnumerablePtr other)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | 用于检查的超集。 |

### 返回值

如果当前集合的所有元素都存在于 **other** 中，并且 **other** 的元素数量多于当前集合，则返回 True，否则返回 false。

## 另见

* 类型定义 [IEnumerablePtr](../ienumerableptr/)
* 类 [ISet](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)