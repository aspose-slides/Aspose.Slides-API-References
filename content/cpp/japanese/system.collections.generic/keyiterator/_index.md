---
title: KeyIterator
second_title: Aspose.Slides for C++ API リファレンス
description: キーアクセスを提供するディクショナリイテレータ。
type: docs
weight: 365
url: /ja/system.collections.generic/keyiterator/
---
## KeyIterator クラス

[Dictionary](../dictionary/) キーへのアクセスを提供するイテレータ。

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| Dict | [Dictionary](../dictionary/) クラス。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | 現在のイテレータをクローンします。 |
| void [DecrementIterator](./decrementiterator/)() override | イテレータを1ステップ後退させます。 |
| void [IncrementIterator](./incrementiterator/)() override | イテレータを1ステップ前進させます。 |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | コンストラクタ。 |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | コンストラクタ。 |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | ムーブコンストラクタ。 |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | 指定されたステップ数だけイテレータを移動させます。 |
| virtual  [~KeyIterator](./~keyiterator/)() | デストラクタ。 |

## 参照

* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)