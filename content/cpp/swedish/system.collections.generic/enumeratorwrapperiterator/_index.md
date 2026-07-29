---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides för C++ API-referens
description: Iterator som omsluter den förhandskapade uppräkningen och omdirigerar alla anrop till den.
type: docs
weight: 196
url: /sv/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator klass


Iterator som omsluter den förhandsskapade uppräkningen och omdirigerar alla anrop till den.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Element | Elementtyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Klonar aktuell iterator. |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | Flyttar iterator ett steg framåt. Måste uppdatera m_is_end och m_pointer. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | Kontrollerar om två iteratorer pekar på samma element. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Destruktor. |

## Se även

* Namnrymd [System::Collections::Generic](../)
* Bibliotek [Aspose.Slides](../../)