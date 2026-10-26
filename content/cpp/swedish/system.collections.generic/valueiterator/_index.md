---
title: ValueIterator
second_title: Aspose.Slides för C++ API-referens
description: Ordboksiterator som ger åtkomst till värden.
type: docs
weight: 625
url: /sv/system.collections.generic/valueiterator/
---
## ValueIterator klass

[Dictionary](../dictionary/) iterator som ger värdeåtkomst.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Dict | [Dictionary](../dictionary/) klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | Klonar aktuell iterator. |
| void [DecrementIterator](./decrementiterator/)() override | Flyttar iteratorn ett steg bakåt. |
| void [IncrementIterator](./incrementiterator/)() override | Flyttar iteratorn ett steg framåt. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Flyttar iteratorn med det angivna antalet steg. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | Flyttkonstruktor. |
| virtual  [~ValueIterator](./~valueiterator/)() | Destruktor. |

## Se även

* Namnrymd [System::Collections::Generic](../)
* Bibliotek [Aspose.Slides](../../)