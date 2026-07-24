---
title: ValueIterator
second_title: Aspose.Slides for C++ API Referansı
description: Değer erişimi sağlayan sözlük yineleyicisi.
type: docs
weight: 625
url: /tr/system.collections.generic/valueiterator/
---
## ValueIterator sınıfı


[Dictionary](../dictionary/) değer erişimi sağlayan yineleme.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Dict | [Dictionary](../dictionary/) sınıf. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | Geçerli yineleyiciyi kopyalar. |
| void [DecrementIterator](./decrementiterator/)() override | Yineleyiciyi bir adım geri hareket ettirir. |
| void [IncrementIterator](./incrementiterator/)() override | Yineleyiciyi bir adım ileri hareket ettirir. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Yineleyiciyi belirtilen adım sayısı kadar hareket ettirir. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Yapıcı. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Yapıcı. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | Taşıma yapıcı. |
| virtual  [~ValueIterator](./~valueiterator/)() | Yıkıcı. |

## Ayrıca bakınız

* Ad alanı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)