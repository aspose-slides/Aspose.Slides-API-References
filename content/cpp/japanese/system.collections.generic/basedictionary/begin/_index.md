---
title: begin()
second_title: Aspose.Slides for C++ API リファレンス
description: コンテナのキー-バリュー要素の KVPair ラッパーへのイテレータを返します。C# スタイルで実装されており、イテレータは get_Key() と get_Value() インターフェイスを持つ KVPair オブジェクトを返す必要があります。コンテナが空の場合、返されるイテレータは end() と等しくなります。
type: docs
weight: 222
url: /ja/system.collections.generic/basedictionary/begin/
---
## BaseDictionary::begin() const メソッド


コンテナのキー-バリュー要素の KVPair ラッパーへのイテレータを返します。C# スタイルで実装されており、イテレータは get_Key() と get_Value() インターフェイスを持つ KVPair オブジェクトを返すべきです。コンテナが空の場合、返されるイテレータは [end()](../../ienumerable/end/) と等しくなります。

```cpp
const_iterator System::Collections::Generic::BaseDictionary<Map>::begin() const noexcept
```


### 戻り値

コレクションの最初の要素を指すイテレータです。

## 参照

* Typedef [const_iterator](../const_iterator/)
* クラス [BaseDictionary](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)