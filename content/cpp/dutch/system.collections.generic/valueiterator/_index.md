---
title: ValueIterator
second_title: Aspose.Slides voor C++ API-referentie
description: Dictionary iterator die toegang tot waarden biedt.
type: docs
weight: 625
url: /nl/system.collections.generic/valueiterator/
---
## ValueIterator klasse

[Dictionary](../dictionary/) iterator die toegang tot waarden biedt.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Dict | [Dictionary](../dictionary/) class. |

## Methoden

| Methode | Beschrijving |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | Kopieert de huidige iterator. |
| void [DecrementIterator](./decrementiterator/)() override | Verplaatst de iterator één stap terug. |
| void [IncrementIterator](./incrementiterator/)() override | Verplaatst de iterator één stap vooruit. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Verplaatst de iterator met het opgegeven aantal stappen. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructor. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructor. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | Move-constructor. |
| virtual  [~ValueIterator](./~valueiterator/)() | Destructor. |

## Zie ook

* namespace [System::Collections::Generic](../)
* Bibliotheek [Aspose.Slides](../../)