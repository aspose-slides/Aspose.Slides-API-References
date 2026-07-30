---
title: DictionaryIterator
second_title: Aspose.Slides pro C++ referenční příručka API
description: Iterátor slovníku, který poskytuje zápis KeyValuePair.
type: docs
weight: 157
url: /cs/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator třída

[Dictionary](../dictionary/) iterátor, který poskytuje [KeyValuePair](../keyvaluepair/) zápis.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Dict | [Dictionary](../dictionary/) třída. |
## Metody

| Metoda | Popis |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | Klonuje aktuální iterátor. |
| void [DecrementIterator](./decrementiterator/)() override | Posouvá iterátor o krok zpět. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | Konstruktor přesunu. |
| void [IncrementIterator](./incrementiterator/)() override | Posouvá iterátor o krok vpřed. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Posouvá iterátor o zadaný počet kroků. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | Destruktor. |

## Viz také

* Jmenný prostor [System::Collections::Generic](../)
* Knihovna [Aspose.Slides](../../)