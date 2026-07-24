---
title: DictionaryIterator
second_title: Aspose.Slides için C++ API Referansı
description: KeyValuePair gösterimini sağlayan sözlük yineleyicisi.
type: docs
weight: 157
url: /tr/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator sınıfı

[Dictionary](../dictionary/) yineleyici, [KeyValuePair](../keyvaluepair/) gösterimini sağlar.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Dict | [Dictionary](../dictionary/) sınıfı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | Geçerli yineleyiciyi klonlar. |
| void [DecrementIterator](./decrementiterator/)() override | Yineleyiciyi bir adım geriye hareket ettirir. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Yapıcı. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Yapıcı. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | Taşıma yapıcı. |
| void [IncrementIterator](./incrementiterator/)() override | Yineleyiciyi bir adım ileri hareket ettirir. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Yineleyiciyi belirtilen adım sayısı kadar hareket ettirir. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | Yıkıcı. |

## Ayrıca Bakınız

* Ad alanı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)