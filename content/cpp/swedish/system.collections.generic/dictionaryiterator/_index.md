---
title: DictionaryIterator
second_title: Aspose.Slides för C++ API-referens
description: Dictionary-iterator som tillhandahåller KeyValuePair-notation.
type: docs
weight: 157
url: /sv/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator klass

[Dictionary](../dictionary/) iterator som tillhandahåller [KeyValuePair](../keyvaluepair/) notation.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Dict | [Dictionary](../dictionary/) klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | Klonar den aktuella iteratorn. |
| void [DecrementIterator](./decrementiterator/)() override | Flyttar iteratorn ett steg bakåt. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | Flyttkonstruktor. |
| void [IncrementIterator](./incrementiterator/)() override | Flyttar iteratorn ett steg framåt. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Flyttar iteratorn med angivet antal steg. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | Destruktor. |

## Se även

* Namnrymd [System::Collections::Generic](../)
* Bibliotek [Aspose.Slides](../../)