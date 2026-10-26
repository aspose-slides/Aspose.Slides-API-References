---
title: KeyIterator
second_title: Riferimento API di Aspose.Slides per C++
description: Iteratore del dizionario che fornisce l'accesso alle chiavi.
type: docs
weight: 365
url: /it/system.collections.generic/keyiterator/
---
## KeyIterator classe


[Dictionary](../dictionary/) iteratore che fornisce l'accesso alle chiavi.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Dict | [Dictionary](../dictionary/) classe. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | Clona l'iteratore corrente. |
| void [DecrementIterator](./decrementiterator/)() override | Sposta l'iteratore indietro di un passo. |
| void [IncrementIterator](./incrementiterator/)() override | Sposta l'iteratore in avanti di un passo. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Costruttore. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Costruttore. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | Costruttore di spostamento. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Sposta l'iteratore di un numero specificato di passi. |
| virtual  [~KeyIterator](./~keyiterator/)() | Distruttore. |

## Vedi anche

* Spazio dei nomi [System::Collections::Generic](../)
* Libreria [Aspose.Slides](../../)