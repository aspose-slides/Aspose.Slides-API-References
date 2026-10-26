---
title: KeyIterator
second_title: Aspose.Slides pro C++ referenční příručku
description: Iterátor slovníku, který poskytuje přístup ke klíčům.
type: docs
weight: 365
url: /cs/system.collections.generic/keyiterator/
---
## KeyIterator třída


[Dictionary](../dictionary/) iterátor, který poskytuje přístup ke klíčům.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Dict | [Dictionary](../dictionary/) třída. |
## Metody

| Metoda | Popis |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | Klonuje aktuální iterátor. |
| void [DecrementIterator](./decrementiterator/)() override | Posune iterátor o krok zpět. |
| void [IncrementIterator](./incrementiterator/)() override | Posune iterátor o krok vpřed. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | Konstruktor přesunu. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Posune iterátor o zadaný počet kroků. |
| virtual  [~KeyIterator](./~keyiterator/)() | Destruktor. |

## Viz také

* Jmenný prostor [System::Collections::Generic](../)
* Knihovna [Aspose.Slides](../../)