---
title: IsSubsetOf()
second_title: Aspose.Slides for C++ API 參考文件
description: 檢查目前的集合是否為其他容器的子集合。
type: docs
weight: 66
url: /zh-hant/system.collections.generic/iset/issubsetof/
---
## ISet::IsSubsetOf(IEnumerablePtr) 方法

檢查目前的集合是否為 other 容器的子集合。

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsSubsetOf(IEnumerablePtr other)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | 用於檢查的上層集合。 |

### 回傳值

如果目前集合中的所有元素皆存在於 **other** 中，則回傳 true，否則回傳 false。

## 另請參閱

* 型別定義 [IEnumerablePtr](../ienumerableptr/)
* 類別 [ISet](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)