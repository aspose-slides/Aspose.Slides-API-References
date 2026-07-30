---
title: DictionaryIterator
second_title: Riferimento API di Aspose.Slides per C++
description: Iteratore di dizionario che fornisce la notazione KeyValuePair.
type: docs
weight: 157
url: /it/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator classe


[Dictionary](../dictionary/) iteratore che fornisce notazione [KeyValuePair](../keyvaluepair/).

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Dict | [Dictionary](../dictionary/) classe. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | Clona l'iteratore corrente. |
| void [DecrementIterator](./decrementiterator/)() override | Sposta l'iteratore indietro di un passo. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Costruttore. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Costruttore. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | Costruttore di spostamento. |
| void [IncrementIterator](./incrementiterator/)() override | Sposta l'iteratore avanti di un passo. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Sposta l'iteratore del numero di passi specificato. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | Distruttore. |

## Vedi anche

* Spazio dei nomi [System::Collections::Generic](../)
* Libreria [Aspose.Slides](../../)