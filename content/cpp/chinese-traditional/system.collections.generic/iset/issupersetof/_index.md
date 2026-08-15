---
title: IsSupersetOf()
second_title: Aspose.Slides for C++ API 參考
description: 檢查目前集合是否為其他容器的超集合。
type: docs
weight: 79
url: /zh-hant/system.collections.generic/iset/issupersetof/
---
## ISet::IsSupersetOf(IEnumerablePtr) 方法

檢查目前集合是否為其他容器的超集合。

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsSupersetOf(IEnumerablePtr other)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | 要檢查的子集合。 |

### 回傳值

若 **other** 中的所有元素皆存在於集合中則回傳 true，否則回傳 false。

## 參見

* 型別定義 [IEnumerablePtr](../ienumerableptr/)
* 類別 [ISet](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)