---
title: end()
second_title: Aspose.Slides for C++ API リファレンス
description: コンテナの最後の要素に続くキーと値の要素の KVPair ラッパーへのイテレータを返します。C# スタイルで実装されており、イテレータは get_Key() および get_Value() インターフェイスを持つ KVPair オブジェクトを返すべきです。この要素はプレースホルダーとして機能し、アクセスしようとすると未定義の動作になります。
type: docs
weight: 235
url: /ja/system.collections.generic/basedictionary/end/
---
## BaseDictionary::end() const メソッド

キーと値の要素に続く KVPair ラッパーへのイテレータを返します。C# スタイルで実装されており、イテレータは get_Key() と get_Value() インターフェイスを持つ KVPair オブジェクトを返すべきです。この要素はプレースホルダーとして機能し、アクセスしようとすると未定義の動作になります。

```cpp
const_iterator System::Collections::Generic::BaseDictionary<Map>::end() const noexcept
```

### 戻り値

コレクションの末尾要素の後に配置される理論上の要素を指すイテレータ。

## 参照

* 型定義 [const_iterator](../const_iterator/)
* クラス [BaseDictionary](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)