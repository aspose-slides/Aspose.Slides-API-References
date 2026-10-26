---
title: EnumeratorWrapperIterator
second_title: Riferimento API Aspose.Slides per C++
description: Iteratore che avvolge l'enumeratore pre-creato e reindirizza tutte le chiamate ad esso.
type: docs
weight: 196
url: /it/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator classe

Iteratore che avvolge l'enumeratore pre-creato e reindirizza tutte le chiamate a esso.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Element | Tipo di elemento. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Clona l'iteratore corrente. |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | Muove l'iteratore di un passo in avanti. Deve aggiornare m_is_end e m_pointer. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | Verifica se due iteratori puntano allo stesso elemento. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Distruttore. |

## Vedi anche

* Spazio dei nomi [System::Collections::Generic](../)
* Libreria [Aspose.Slides](../../)