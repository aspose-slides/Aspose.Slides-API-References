---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Iterátor, který obaluje předem vytvořený enumerátor a přesměrovává do něj všechna volání.
type: docs
weight: 196
url: /cs/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator třída

Iterátor, který obaluje předem vytvořený enumerátor a přesměrovává všechny volání do něj.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Element | Typ Elementu. |
## Metody

| Metoda | Popis |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Klonuje aktuální iterátor. |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | Posouvá iterátor o krok vpřed. Musí aktualizovat m_is_end a m_pointer. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | Kontroluje, zda dva iterátory ukazují na stejnou položku. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Destruktor. |

## Viz také

* Jmenný prostor [System::Collections::Generic](../)
* Knihovna [Aspose.Slides](../../)