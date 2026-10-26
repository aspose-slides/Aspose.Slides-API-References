---
title: IsProperSubsetOf()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のセットが他のコンテナの厳密な部分集合であるかを確認します。
type: docs
weight: 40
url: /ja/system.collections.generic/iset/ispropersubsetof/
---
## ISet::IsProperSubsetOf(IEnumerablePtr) メソッド

現在のセットが他のコンテナの厳密な部分集合であるかを確認します。

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsProperSubsetOf(IEnumerablePtr other)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | 比較対象となる上位集合。 |

### 戻り値

現在のセットのすべての要素が **other** に存在し、かつ **other** の要素数が現在のセットより多い場合は true、そうでなければ false。

## 参照

* Typedef [IEnumerablePtr](../ienumerableptr/)
* クラス [ISet](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)