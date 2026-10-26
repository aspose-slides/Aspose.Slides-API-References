---
title: EqualityComparerAdapter
second_title: Aspose.Slides for C++ API リファレンス
description: "IEqualityComparer を使用して STL 形式のコレクションやアルゴリズムを可能にするアダプタです。設定されている場合は IEqualityComparer を使用します。設定されていない場合は、operator ==、Object::Equals、または T::Equals のいずれか利用可能なものを使用します。"
type: docs
weight: 664
url: /ja/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter 構造体

Adapter making it possible using [IEqualityComparer](../iequalitycomparer/) with STL-styled collections and algorithms. Uses [IEqualityComparer](../iequalitycomparer/), if set. If not set, uses operator ==, [Object::Equals](../../system/object/equals/) or T::Equals, whichever is available.

```cpp
template<class T>class EqualityComparerAdapter
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | 比較対象の型。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | コンパレーターを使用せずにアダプターを作成します。 |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | 指定されたコンパレーターでアダプターを作成します。 |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | 2 つのオブジェクトを比較します。 |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | コンパレーターを設定します。 |

## 参照

* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)