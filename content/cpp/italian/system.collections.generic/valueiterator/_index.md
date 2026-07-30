---
title: ValueIterator
second_title: Riferimento API di Aspose.Slides per C++
description: Iteratore del dizionario che fornisce l'accesso al valore.
type: docs
weight: 625
url: /it/system.collections.generic/valueiterator/
---
## ValueIterator classe


[Dictionary](../dictionary/) iteratore che fornisce l'accesso al valore.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Dict | [Dictionary](../dictionary/) classe. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | Clona l'iteratore corrente. |
| void [DecrementIterator](./decrementiterator/)() override | Sposta l'iteratore di un passo indietro. |
| void [IncrementIterator](./incrementiterator/)() override | Sposta l'iteratore di un passo avanti. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Sposta l'iteratore del numero specificato di passi. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Costruttore. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Costruttore. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | Costruttore di spostamento. |
| virtual  [~ValueIterator](./~valueiterator/)() | Distruttore. |

## Vedi anche

* Spazio dei nomi [System::Collections::Generic](../)
* Libreria [Aspose.Slides](../../)