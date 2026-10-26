---
title: LINQ_GroupBy()
second_title: Aspose.Slides for C++ API リファレンス
description: シーケンスの要素をグループ化します。
type: docs
weight: 287
url: /ja/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) メソッド

シーケンスの要素をグループ化します。

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| Key | keyPredicate によって返されるキーの型 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | 各要素からキーを抽出する関数。 |

### 戻り値

[IEnumerable](../) はオブジェクトのシーケンスとキーを含むものです。

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) メソッド

シーケンスの要素をグループ化します。

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| Key | keyPredicate によって返されるキーの型 |
| Element | elementSelector によって返される要素の型 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | 各要素からキーを抽出する関数。 |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | 各要素から値キーを抽出する関数。 |

### 戻り値

[IEnumerable](../) はオブジェクトのシーケンスとキーを含むものです。

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) メソッド




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) メソッド




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IEnumerable](../)
* クラス [IGrouping](../../../system.linq/igrouping/)
* クラス [Func](../../../system/func/)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)