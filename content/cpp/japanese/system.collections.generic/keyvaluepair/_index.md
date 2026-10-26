---
title: KeyValuePair
second_title: Aspose.Slides for C++ API リファレンス
description: "キーと値のペア。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。この型のオブジェクトを管理するために System::SmartPtr クラスを使用しないでください。"
type: docs
weight: 378
url: /ja/system.collections.generic/keyvaluepair/
---
## KeyValuePair クラス

キーと値のペア。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。[System::SmartPtr](../../system/smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | キーを取得します。 |
| const TValue\& [get_Value](./get_value/)() const | 値を取得します。 |
| int [GetHashCode](./gethashcode/)() const | キーと値のハッシュを XOR してキーと値のペアのハッシュを計算します。 |
| **bool** [IsNull](./isnull/)() const | 常に false を返します。 |
|  [KeyValuePair](./keyvaluepair/)() | ヌルキー・バリューペアの初期化子。 |
|  [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | コンストラクタ。 |
|  [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | 型変換コンストラクタ。 |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | IComparer<KeyValuePair<TKey, TValue>> から継承されたクラス用のパッチで、何も比較しません。 |
| [String](../../system/string/) [ToString](./tostring/)() const | キーとバリューのペアを文字列に変換します。 |

## 参照

* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)