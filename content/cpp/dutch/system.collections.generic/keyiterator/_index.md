---
title: KeyIterator
second_title: Aspose.Slides voor C++ API-referentie
description: Woordenboek-iterator die toegang tot sleutels biedt.
type: docs
weight: 365
url: /nl/system.collections.generic/keyiterator/
---
## KeyIterator klasse


[Dictionary](../dictionary/) iterator die toegang tot sleutels biedt.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Dict | [Dictionary](../dictionary/) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | Kopieert de huidige iterator. |
| void [DecrementIterator](./decrementiterator/)() override | Beweegt de iterator een stap terug. |
| void [IncrementIterator](./incrementiterator/)() override | Beweegt de iterator een stap vooruit. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructor. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructor. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | Move constructor. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Beweegt de iterator met het opgegeven aantal stappen. |
| virtual  [~KeyIterator](./~keyiterator/)() | Destructor. |

## Zie ook

* Naamruimte [System::Collections::Generic](../)
* Bibliotheek [Aspose.Slides](../../)