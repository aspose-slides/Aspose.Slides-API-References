---
title: LINQ_OrderBy()
second_title: Aspose.Slides for C++ API リファレンス
description: keySelector が選択したキー値に従って、シーケンスの要素を昇順に並べ替えます。
type: docs
weight: 209
url: /ja/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) メソッド

シーケンスの要素を、keySelector が選択したキー値に従って昇順に並べ替えます。

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| keySelector | 要素からキーを抽出する関数。 |

### 戻り値

キーに従って要素がソートされた IOrderedEnumerable

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) メソッド

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* クラス [Func](../../../system/func/)
* クラス [IEnumerable](../)
* 名前空間 [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)