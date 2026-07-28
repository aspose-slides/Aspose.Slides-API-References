---
title: DictionaryIterator
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Iterator słownika zapewniający notację KeyValuePair.
type: docs
weight: 157
url: /pl/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator klasa

[Dictionary](../dictionary/) iterator, który zapewnia notację [KeyValuePair](../keyvaluepair/).

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Dict | [Dictionary](../dictionary/) klasa. |

## Metody

| Metoda | Opis |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | Klonuje bieżący iterator. |
| void [DecrementIterator](./decrementiterator/)() override | Przesuwa iterator o krok wstecz. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | Konstruktor przenoszący. |
| void [IncrementIterator](./incrementiterator/)() override | Przesuwa iterator o krok naprzód. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Przesuwa iterator o określoną liczbę kroków. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | Destruktor. |

## Zobacz także

* Przestrzeń nazw [System::Collections::Generic](../)
* Biblioteka [Aspose.Slides](../../)