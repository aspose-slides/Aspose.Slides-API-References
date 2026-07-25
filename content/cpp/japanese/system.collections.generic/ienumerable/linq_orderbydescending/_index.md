---
title: LINQ_OrderByDescending()
second_title: Aspose.Slides for C++ API リファレンス
description: シーケンスの要素を、keySelector によって選択されたキー値に基づき、降順に並べ替えます。
type: docs
weight: 222
url: /ja/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) メソッド

シーケンスの要素を、keySelector によって選択されたキー値に基づき、降順に並べ替えます。

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| keySelector | 要素からキーを抽出する関数。 |

### 戻り値

キーの降順に要素がソートされた IOrderedEnumerable

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) メソッド

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* クラス [Func](../../../system/func/)
* クラス [IEnumerable](../)
* 名前空間 [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)