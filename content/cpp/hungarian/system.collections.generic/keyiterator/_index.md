---
title: KeyIterator
second_title: Aspose.Slides C++ API hivatkozás
description: Szótár iterátor, amely kulcs hozzáférést biztosít.
type: docs
weight: 365
url: /hu/system.collections.generic/keyiterator/
---
## KeyIterator osztály


[Dictionary](../dictionary/) egy iterátor, amely kulcs hozzáférést biztosít.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Dict | [Dictionary](../dictionary/) osztály. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | Klónozza a jelenlegi iterátort. |
| void [DecrementIterator](./decrementiterator/)() override | Az iterátort egy lépéssel visszalépteti. |
| void [IncrementIterator](./incrementiterator/)() override | Az iterátort egy lépéssel előrelépteti. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | Áthelyező konstruktor. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Az iterátort a megadott számú lépéssel mozgatja. |
| virtual  [~KeyIterator](./~keyiterator/)() | Destruktor. |

## Lásd még

* Névtere [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)