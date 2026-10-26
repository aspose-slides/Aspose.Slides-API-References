---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides voor C++ API-referentie
description: Iterator die de vooraf aangemaakte enumerator omsluit en alle oproepen ernaar doorstuurt.
type: docs
weight: 196
url: /nl/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator klasse

Iterator die de vooraf aangemaakte enumerator omsluit en alle oproepen ernaar doorstuurt.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Element | Elementtype. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Kloont de huidige iterator. |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | Verplaatst de iterator een stap vooruit. Moet m_is_end en m_pointer bijwerken. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | Controleert of twee iteratoren naar hetzelfde item wijzen. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Destructeur. |

## Zie ook

* Namespace [System::Collections::Generic](../)
* Bibliotheek [Aspose.Slides](../../)