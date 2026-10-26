---
title: ValueIterator
second_title: Aspose.Slides pro C++ referenci API
description: Iterátor slovníku, který poskytuje přístup k hodnotě.
type: docs
weight: 625
url: /cs/system.collections.generic/valueiterator/
---
## ValueIterator třída


[Dictionary](../dictionary/) iterator, který poskytuje přístup k hodnotě.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Dict | [Dictionary](../dictionary/) třída. |
## Metody

| Metoda | Popis |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | Klonuje aktuální iterator. |
| void [DecrementIterator](./decrementiterator/)() override | Posouvá iterator o krok zpět. |
| void [IncrementIterator](./incrementiterator/)() override | Posouvá iterator o krok vpřed. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Posouvá iterator o zadaný počet kroků. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | Konstruktor přesunu. |
| virtual  [~ValueIterator](./~valueiterator/)() | Destruktor. |

## Viz také

* Jmenný prostor [System::Collections::Generic](../)
* Knihovna [Aspose.Slides](../../)