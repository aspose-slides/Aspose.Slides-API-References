---
title: EqualityComparerHashAdapter
second_title: Aspose.Slides for C++ API リファレンス
description: ハッシュ計算に IEqualityComparer を使用するためのアダプターです。コンパレータオブジェクトが設定されている場合はそれを使用し、設定されていない場合は DictionaryHashSelector 構造体で選択された利用可能なハッシュメソッドを使用します。
type: docs
weight: 677
url: /ja/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter 構造体


ハッシュ計算に [IEqualityComparer](../iequalitycomparer/) を使用するためのアダプターです。コンパレータオブジェクトが設定されている場合はそれを使用し、設定されていない場合は [DictionaryHashSelector](../dictionaryhashselector/) 構造体で選択された利用可能なハッシュメソッドを使用します。

```cpp
template<typename T>class EqualityComparerHashAdapter
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| Hashed | 型。 |
## メソッド

| Method | Description |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | コンパレータを使用せずにアダプターを作成します。 |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | 指定されたコンパレータを使用してアダプターを作成します。 |
| std::size_t [operator()](./operator_call/)(const T\&) const | ハッシュ値を計算します。 |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | 使用するコンパレータを設定します。 |

## 参照

* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)