---
title: operator()()
second_title: Aspose.Slides for C++ API リファレンス
description: IComparable インターフェイスを実装しているポインタ型を比較します。
type: docs
weight: 1
url: /ja/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const メソッド

[IComparable](../../../system/icomparable/) インターフェイスを実装しているポインタ型を比較します。

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Q | 比較対象の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | 左辺値。 |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | 右辺値。 |

### 戻り値

True if **a** is considered less than **b**, false otherwise.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const メソッド

[IComparable](../../../system/icomparable/) インターフェイスを実装していないポインタ型を比較します。

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Q | 比較対象の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | 左辺値。 |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | 右辺値。 |

### 戻り値

True if **a** is considered less than **b**, false otherwise.

## 関連項目

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IComparable](../../../system/icomparable/)
* 構造体 [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* 構造体 [ComparerType< SharedPtr< T > >](../)
* 名前空間 [System::Collections::Generic::Details](../../)
* ライブラリ [Aspose.Slides](../../../)