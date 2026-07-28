---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides dla C++ – Referencja API
description: Iterator, który otacza wcześniej utworzony enumerator i przekierowuje wszystkie wywołania do niego.
type: docs
weight: 196
url: /pl/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator klasa

Iterator który otacza wcześniej utworzony enumerator i przekierowuje wszystkie wywołania do niego.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Element | Typ elementu. |

## Metody

| Metoda | Opis |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Klonuje bieżący iterator. |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | Przesuwa iterator o krok do przodu. Musi zaktualizować m_is_end i m_pointer. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | Sprawdza, czy dwa iteratory wskazują na ten sam element. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Destruktor. |

## Zobacz także

* Przestrzeń nazw [System::Collections::Generic](../)
* Biblioteka [Aspose.Slides](../../)