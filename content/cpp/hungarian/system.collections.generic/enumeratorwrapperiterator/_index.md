---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides for C++ API referencia
description: Az előre létrehozott enumerátort becsomagoló iterátor, amely minden hívást átirányít rá.
type: docs
weight: 196
url: /hu/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator osztály

Az előre létrehozott enumerátort becsomagoló iterátor, amely minden hívást átirányít rá.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Element | Element típus. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Klónozza az aktuális iterátort. |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | Az iterátort egy lépéssel előre mozgatja. Frissítenie kell az m_is_end és az m_pointer változókat. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | Ellenőrzi, hogy két iterátor ugyanarra az elemre mutat-e. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Megsemmisítő. |

## Lásd még

* Névtér [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)