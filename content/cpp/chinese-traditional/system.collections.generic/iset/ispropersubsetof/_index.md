---
title: IsProperSubsetOf()
second_title: Aspose.Slides for C++ API 參考文件
description: 檢查當前集合是否為另一個容器的嚴格子集。
type: docs
weight: 40
url: /zh-hant/system.collections.generic/iset/ispropersubsetof/
---
## ISet::IsProperSubsetOf(IEnumerablePtr) 方法


檢查當前集合是否為另一個容器的嚴格子集。

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsProperSubsetOf(IEnumerablePtr other)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | 要檢查的上層集合。 |

### 返回值

如果當前集合的所有元素都存在於 **other** 中，且 **other** 的元素數量多於當前集合，則返回 true，否則返回 false。

## 另請參閱

* Typedef [IEnumerablePtr](../ienumerableptr/)
* Class [ISet](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)