---
title: DictionaryIterator
second_title: Aspose.Slides para C++ Referência da API
description: Iterador de dicionário que fornece notação KeyValuePair.
type: docs
weight: 157
url: /pt/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator classe

[Dictionary](../dictionary/) iterador que fornece notação [KeyValuePair](../keyvaluepair/).

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Dict | [Dictionary](../dictionary/) classe. |
## Métodos

| Método | Descrição |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | Clona o iterador atual. |
| void [DecrementIterator](./decrementiterator/)() override | Move o iterador um passo para trás. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Construtor. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Construtor. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | Construtor de movimento. |
| void [IncrementIterator](./incrementiterator/)() override | Move o iterador um passo adiante. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Move o iterador pelo número de passos especificado. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | Destrutor. |

## Ver também

* Espaço de nomes [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)