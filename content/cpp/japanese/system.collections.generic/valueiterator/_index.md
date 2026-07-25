---
title: ValueIterator
second_title: Aspose.Slides for C++ API リファレンス
description: 値へのアクセスを提供する辞書イテレータ。
type: docs
weight: 625
url: /ja/system.collections.generic/valueiterator/
---
## ValueIterator クラス


[Dictionary](../dictionary/) iterator that provides value access.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| Dict | [Dictionary](../dictionary/) クラス。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | 現在のイテレータをクローンします。 |
| void [DecrementIterator](./decrementiterator/)() override | イテレータを1ステップ戻します。 |
| void [IncrementIterator](./incrementiterator/)() override | イテレータを1ステップ進めます。 |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | 指定されたステップ数だけイテレータを移動します。 |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | コンストラクタ。 |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | コンストラクタ。 |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | ムーブコンストラクタ。 |
| virtual  [~ValueIterator](./~valueiterator/)() | デストラクタ。 |

## 参照

* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)