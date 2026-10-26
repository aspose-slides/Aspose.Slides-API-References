---
title: DictionaryIterator
second_title: Aspose.Slides for C++ API リファレンス
description: KeyValuePair 表記を提供するディクショナリ イテレータ。
type: docs
weight: 157
url: /ja/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator クラス


[Dictionary](../dictionary/) イテレータは [KeyValuePair](../keyvaluepair/) 表記を提供します。

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Dict | [Dictionary](../dictionary/) クラス。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | 現在のイテレータをクローンします。 |
| void [DecrementIterator](./decrementiterator/)() override | イテレータを1ステップ戻します。 |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | コンストラクタ。 |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | コンストラクタ。 |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | ムーブ コンストラクタ。 |
| void [IncrementIterator](./incrementiterator/)() override | イテレータを1ステップ進めます。 |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | 指定されたステップ数だけイテレータを移動します。 |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | デストラクタ。 |

## 参照

* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)