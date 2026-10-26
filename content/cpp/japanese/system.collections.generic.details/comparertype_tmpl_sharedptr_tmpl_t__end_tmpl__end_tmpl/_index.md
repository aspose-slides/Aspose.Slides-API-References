---
title: ComparerType< SharedPtr< T > >
second_title: Aspose.Slides for C++ API リファレンス
description: 要素を「less」セマンティクスで比較します。
type: docs
weight: 157
url: /ja/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct

要素を 'less' セマンティクスで比較します。

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 比較対象となる要素の型。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | [IComparable](../../system/icomparable/) インターフェイスを実装しているポインタ型を比較します。 |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | [IComparable](../../system/icomparable/) インターフェイスを実装していないポインタ型を比較します。 |

## 参照

* 名前空間 [System::Collections::Generic::Details](../)
* ライブラリ [Aspose.Slides](../../)