---
title: LINQ_ThenBy()
second_title: Aspose.Slides for C++ API リファレンス
description: キーに基づいてシーケンス内の要素を昇順に後続で並び替えます。
type: docs
weight: 27
url: /ja/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) メソッド

シーケンス内の要素をキーに基づいて昇順に後続の並べ替えを実行します。

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Key | keySelector が返すキーの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | 各要素からキーを抽出する関数。 |

### 戻り値

[System::Linq::IOrderedEnumerable](../) の要素がキーに基づいてソートされたもの。

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) メソッド

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IOrderedEnumerable](../)
* クラス [Func](../../../system/func/)
* 名前空間 [System::Linq](../../)
* Library [Aspose.Slides](../../../)