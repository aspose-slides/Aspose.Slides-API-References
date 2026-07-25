---
title: AbstractEqual()
second_title: Aspose.Slides for C++ API リファレンス
description: 不明な型の 2 つのコレクションを比較します。
type: docs
weight: 14
url: /ja/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) メソッド

不明な型の 2 つのコレクションを比較します。

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | コレクション要素の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | 左側コレクション。 |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | 右側コレクション。 |

### 戻り値

コレクションが一致する場合 (例: 両方が null)、またはサイズが一致し要素が一致する場合は true、そうでない場合は false。

## 参照

* クラス [ICollection](../../../system.collections.generic/icollection/)
* 構造体 [TestCompare](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)