---
title: ValueIterator
second_title: Aspose.Slides C++ API referencia
description: Szótár iterátor, amely értékhozzáférést biztosít.
type: docs
weight: 625
url: /hu/system.collections.generic/valueiterator/
---
## ValueIterator osztály


[Dictionary](../dictionary/) iterátor, amely értékhozzáférést biztosít.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Dict | [Dictionary](../dictionary/) osztály. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | Klónozza a jelenlegi iterátort. |
| void [DecrementIterator](./decrementiterator/)() override | Az iterátort egy lépéssel visszalépteti. |
| void [IncrementIterator](./incrementiterator/)() override | Az iterátort egy lépéssel előrelépteti. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Az iterátort a megadott számú lépéssel mozgatja. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | Mozgató konstruktor. |
| virtual  [~ValueIterator](./~valueiterator/)() | Destruktor. |

## Lásd még

* Névtér [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)