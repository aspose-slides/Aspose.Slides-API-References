---
title: ComparerType
second_title: Aspose.Slides for C++ API リファレンス
description: 要素を 'less' セマンティクスで比較します。
type: docs
weight: 144
url: /ja/system.collections.generic.details/comparertype/
---
## ComparerType 構造体

要素を 'less' セマンティクスで比較します。

```cpp
template<typename T>class ComparerType
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 比較対象要素の型。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [IComparable](../../system/icomparable/) インターフェイスを実装する値型を比較します。 |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [IComparable](../../system/icomparable/) インターフェイスを実装していないプリミティブ値型とオブジェクトを比較します。 |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | 浮動小数点型を比較します。 |

## 参照

* 名前空間 [System::Collections::Generic::Details](../)
* ライブラリ [Aspose.Slides](../../)