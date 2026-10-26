---
title: ValueIterator
second_title: Referência da API Aspose.Slides para C++
description: Iterador de dicionário que fornece acesso ao valor.
type: docs
weight: 625
url: /pt/system.collections.generic/valueiterator/
---
## ValueIterator classe


[Dictionary](../dictionary/) iterador que fornece acesso ao valor.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Dict | [Dictionary](../dictionary/) classe. |
## Métodos

| Método | Descrição |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | Clona o iterador atual. |
| void [DecrementIterator](./decrementiterator/)() override | Move o iterador um passo para trás. |
| void [IncrementIterator](./incrementiterator/)() override | Move o iterador um passo para frente. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Move o iterador pelo número especificado de passos. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Construtor. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Construtor. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | Construtor de movimentação. |
| virtual  [~ValueIterator](./~valueiterator/)() | Destrutor. |

## Ver também

* Espaço de nomes [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)