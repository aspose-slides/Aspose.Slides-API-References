---
title: DictionaryIterator
second_title: Aspose.Slides for C++ API referenciája
description: Szótár iterátor, amely a KeyValuePair notációt biztosítja.
type: docs
weight: 157
url: /hu/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator osztály

[Dictionary](../dictionary/) iterátor, amely biztosítja a [KeyValuePair](../keyvaluepair/) notációt.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Dict | [Dictionary](../dictionary/) osztály. |

## Módszerek

| Módszer | Leírás |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | Klónozza a jelenlegi iterátort. |
| void [DecrementIterator](./decrementiterator/)() override | Az iterátort egy lépéssel visszalépteti. |
| [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
| [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
| [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | Mozgató konstruktor. |
| void [IncrementIterator](./incrementiterator/)() override | Az iterátort egy lépéssel előrelépteti. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Az iterátort a megadott lépésszámmal mozgatja. |
| virtual [~DictionaryIterator](./~dictionaryiterator/)() | Destruktor. |

## Lásd még

* Névtér [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)