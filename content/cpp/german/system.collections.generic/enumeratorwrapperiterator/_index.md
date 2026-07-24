---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides für C++ API-Referenz
description: Iterator, der den vorab erstellten Enumerator kapselt und alle Aufrufe an ihn weiterleitet.
type: docs
weight: 196
url: /de/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator Klasse

Iterator, der den vorab erstellten Enumerator kapselt und alle Aufrufe an ihn weiterleitet.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Element | Elementtyp. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Klonen des aktuellen Iterators. |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | Bewegt den Iterator einen Schritt vorwärts. Muss m_is_end und m_pointer aktualisieren. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | Überprüft, ob zwei Iteratoren auf dasselbe Element zeigen. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Destruktor. |

## Siehe auch

* Namensraum [System::Collections::Generic](../)
* Bibliothek [Aspose.Slides](../../)