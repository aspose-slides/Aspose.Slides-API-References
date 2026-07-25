---
title: ComparerAdapter
second_title: Aspose.Slides for C++ API リファレンス
description: STL 環境内で IComparer を使用するためのアダプターです。IComparer が設定されている場合はそれを使用し、設定されていない場合は operator < (利用可能な場合) を使用するか、利用できない場合は false を返します。
type: docs
weight: 638
url: /ja/system.collections.generic/compareradapter/
---
## ComparerAdapter 構造体

STL 環境内で [IComparer](../icomparer/) を使用するためのアダプターです。[IComparer](../icomparer/) が設定されている場合はそれを使用し、設定されていない場合は operator < (利用可能な場合) を使用するか、利用できない場合は false を返します。

```cpp
template<class T>class ComparerAdapter
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 比較対象の型。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | 利用可能な比較器がない状態でアダプターを構築します。 |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | アダプターを構築します。 |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) 関数（operator < が利用可能な型用）。 |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) 関数（operator < が利用できない型用）。 |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | 比較器オブジェクトを設定します。 |

## 参照

* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)