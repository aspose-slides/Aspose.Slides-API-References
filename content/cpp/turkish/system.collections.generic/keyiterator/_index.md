---
title: KeyIterator
second_title: Aspose.Slides for C++ API Referansı
description: Anahtar erişimi sağlayan sözlük yineleyicisi.
type: docs
weight: 365
url: /tr/system.collections.generic/keyiterator/
---
## KeyIterator sınıfı

[Dictionary](../dictionary/) iterator that provides key access.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Dict | [Dictionary](../dictionary/) sınıf. |

## Metotlar

| Metot | Açıklama |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | Mevcut yineleyiciyi klonlar. |
| void [DecrementIterator](./decrementiterator/)() override | Yineleyiciyi bir adım geriye hareket ettirir. |
| void [IncrementIterator](./incrementiterator/)() override | Yineleyiciyi bir adım ileri hareket ettirir. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Yapıcı. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Yapıcı. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | Taşıma yapıcı. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Yineleyiciyi belirtilen adım sayısı kadar hareket ettirir. |
| virtual  [~KeyIterator](./~keyiterator/)() | Yıkıcı. |

## Ayrıca Bakınız

* ad alanı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)