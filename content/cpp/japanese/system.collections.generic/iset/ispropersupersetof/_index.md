---
title: IsProperSupersetOf()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在の集合が他のコンテナの厳密な上位集合であるかどうかを確認します。
type: docs
weight: 53
url: /ja/system.collections.generic/iset/ispropersupersetof/
---
## ISet::IsProperSupersetOf(IEnumerablePtr) メソッド

現在の集合が他のコンテナの厳密な上位集合であるかどうかを確認します。

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsProperSupersetOf(IEnumerablePtr other)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | 確認対象となる部分集合。 |

### 戻り値

True if all elements in **other** are present in set and set has more elements that **other**, false otherwise.

## 参照

* Typedef [IEnumerablePtr](../ienumerableptr/)
* クラス [ISet](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)