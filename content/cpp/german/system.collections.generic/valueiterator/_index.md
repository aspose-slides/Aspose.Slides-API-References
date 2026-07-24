---
title: ValueIterator
second_title: Aspose.Slides für C++ API-Referenz
description: Dictionary-Iterator, der Zugriff auf Werte bietet.
type: docs
weight: 625
url: /de/system.collections.generic/valueiterator/
---
## ValueIterator Klasse

[Dictionary](../dictionary/) iterator, der Zugriff auf Werte bietet.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Dict | [Dictionary](../dictionary/) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | Klonen des aktuellen Iterators. |
| void [DecrementIterator](./decrementiterator/)() override | Bewegt den Iterator einen Schritt zurück. |
| void [IncrementIterator](./incrementiterator/)() override | Bewegt den Iterator einen Schritt vorwärts. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Bewegt den Iterator um die angegebene Anzahl von Schritten. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | Move-Konstruktor. |
| virtual  [~ValueIterator](./~valueiterator/)() | Destruktor. |

## Siehe auch

* Namensraum [System::Collections::Generic](../)
* Bibliothek [Aspose.Slides](../../)