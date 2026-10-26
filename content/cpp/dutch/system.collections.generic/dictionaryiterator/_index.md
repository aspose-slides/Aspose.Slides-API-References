---
title: DictionaryIterator
second_title: Aspose.Slides voor C++ API-referentie
description: Dictionary-iterator die KeyValuePair-notatie biedt.
type: docs
weight: 157
url: /nl/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator klasse

[Dictionary](../dictionary/) iterator die [KeyValuePair](../keyvaluepair/) notatie biedt.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Dict | [Dictionary](../dictionary/) klasse. |

## Methoden

| Methode | Beschrijving |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | Kloont huidige iterator. |
| void [DecrementIterator](./decrementiterator/)() override | Verplaatst de iterator één stap terug. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructor. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructor. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | Move-constructor. |
| void [IncrementIterator](./incrementiterator/)() override | Verplaatst de iterator één stap vooruit. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Verplaatst de iterator met het opgegeven aantal stappen. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | Destructor. |

## Zie ook

* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)