---
title: IsSubsetOf()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のセットが別のコンテナの部分集合であるかどうかを確認します。
type: docs
weight: 66
url: /ja/system.collections.generic/iset/issubsetof/
---
## ISet::IsSubsetOf(IEnumerablePtr) メソッド


現在の集合が他のコンテナの部分集合であるかどうかを確認します。

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsSubsetOf(IEnumerablePtr other)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | 比較対象となる上位集合。 |

### 戻り値

現在の集合の全要素が **other** に存在すれば true、そうでなければ false を返します。

## 参照

* Typedef [IEnumerablePtr](../ienumerableptr/)
* Class [ISet](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)