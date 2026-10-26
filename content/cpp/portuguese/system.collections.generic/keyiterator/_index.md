---
title: KeyIterator
second_title: Aspose.Slides para C++ Referência da API
description: Iterador de dicionário que fornece acesso à chave.
type: docs
weight: 365
url: /pt/system.collections.generic/keyiterator/
---
## KeyIterator classe

[Dictionary](../dictionary/) iterador que fornece acesso à chave.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Dict | [Dictionary](../dictionary/) classe. |

## Métodos

| Método | Descrição |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | Clona o iterador atual. |
| void [DecrementIterator](./decrementiterator/)() override | Move o iterador um passo para trás. |
| void [IncrementIterator](./incrementiterator/)() override | Move o iterador um passo à frente. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Construtor. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Construtor. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | Construtor de movimentação. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Move o iterador pelo número especificado de passos. |
| virtual  [~KeyIterator](./~keyiterator/)() | Destrutor. |

## Veja Também

* Espaço de nomes [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)