---
title: KeyIterator
second_title: Aspose.Slides dla C++ - odniesienie API
description: Iterator słownika zapewniający dostęp do klucza.
type: docs
weight: 365
url: /pl/system.collections.generic/keyiterator/
---
## KeyIterator klasa


[Dictionary](../dictionary/) iterator zapewniający dostęp do klucza.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Dict | [Dictionary](../dictionary/) klasa. |
## Metody

| Metoda | Opis |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | Klonuje aktualny iterator. |
| void [DecrementIterator](./decrementiterator/)() override | Przesuwa iterator o krok wstecz. |
| void [IncrementIterator](./incrementiterator/)() override | Przesuwa iterator o krok do przodu. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | Konstruktor przenoszący. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Przesuwa iterator o określoną liczbę kroków. |
| virtual  [~KeyIterator](./~keyiterator/)() | Destruktor. |

## Zobacz także

* Przestrzeń nazw [System::Collections::Generic](../)
* Biblioteka [Aspose.Slides](../../)