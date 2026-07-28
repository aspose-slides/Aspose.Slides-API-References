---
title: ValueIterator
second_title: Aspose.Slides dla C++ - odniesienie API
description: Iterator słownika zapewniający dostęp do wartości.
type: docs
weight: 625
url: /pl/system.collections.generic/valueiterator/
---
## ValueIterator klasa


[Dictionary](../dictionary/) iterator który zapewnia dostęp do wartości.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Dict | [Dictionary](../dictionary/) klasa. |
## Metody

| Metoda | Opis |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | Klonuje bieżący iterator. |
| void [DecrementIterator](./decrementiterator/)() override | Przesuwa iterator o krok wstecz. |
| void [IncrementIterator](./incrementiterator/)() override | Przesuwa iterator o krok do przodu. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Przesuwa iterator o określoną liczbę kroków. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | Konstruktor przenoszący. |
| virtual  [~ValueIterator](./~valueiterator/)() | Destruktor. |

## Zobacz także

* Przestrzeń nazw [System::Collections::Generic](../)
* Biblioteka [Aspose.Slides](../../)