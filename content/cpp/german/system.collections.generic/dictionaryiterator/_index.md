---
title: DictionaryIterator
second_title: Aspose.Slides für C++ API-Referenz
description: Dictionary-Iterator, der die KeyValuePair-Notation bereitstellt.
type: docs
weight: 157
url: /de/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator Klasse

[Dictionary](../dictionary/) Iterator, der [KeyValuePair](../keyvaluepair/) Notation bereitstellt.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Dict | [Dictionary](../dictionary/) Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | Kloniert den aktuellen Iterator. |
| void [DecrementIterator](./decrementiterator/)() override | Bewegt den Iterator einen Schritt zurück. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | Move-Konstruktor. |
| void [IncrementIterator](./incrementiterator/)() override | Bewegt den Iterator einen Schritt vorwärts. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Bewegt den Iterator um die angegebene Anzahl von Schritten. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | Destruktor. |

## Siehe auch

* Namensraum [System::Collections::Generic](../)
* Bibliothek [Aspose.Slides](../../)