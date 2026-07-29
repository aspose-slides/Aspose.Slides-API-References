---
title: KeyIterator
second_title: Aspose.Slides för C++ API-referens
description: Ordboksiterator som ger nyckelåtkomst.
type: docs
weight: 365
url: /sv/system.collections.generic/keyiterator/
---
## KeyIterator klass


[Dictionary](../dictionary/) iterator som ger nyckelåtkomst.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Dict | [Dictionary](../dictionary/) klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | Klonar aktuell iterator. |
| void [DecrementIterator](./decrementiterator/)() override | Flyttar iteratorn ett steg bakåt. |
| void [IncrementIterator](./incrementiterator/)() override | Flyttar iteratorn ett steg framåt. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | Flyttkonstruktor. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Flyttar iteratorn med det angivna antalet steg. |
| virtual  [~KeyIterator](./~keyiterator/)() | Destruktor. |

## Se också

* Namnrymd [System::Collections::Generic](../)
* Bibliotek [Aspose.Slides](../../)