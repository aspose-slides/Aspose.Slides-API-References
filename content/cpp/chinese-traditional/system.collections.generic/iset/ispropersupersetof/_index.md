---
title: IsProperSupersetOf()
second_title: Aspose.Slides for C++ API 參考文件
description: 檢查目前的集合是否為其他容器的嚴格上位集合。
type: docs
weight: 53
url: /zh-hant/system.collections.generic/iset/ispropersupersetof/
---
## ISet::IsProperSupersetOf(IEnumerablePtr) 方法


檢查目前的集合是否為其他容器的嚴格上位集合。

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsProperSupersetOf(IEnumerablePtr other)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | 要檢查的子集。 |

### 回傳值

如果集合中所有 **other** 的元素皆存在且集合的元素比 **other** 更多，則回傳 True；否則回傳 false。

## 另請參閱

* 型別別名 [IEnumerablePtr](../ienumerableptr/)
* 類別 [ISet](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)