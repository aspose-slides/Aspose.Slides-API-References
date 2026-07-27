---
title: DictionaryIterator
second_title: Referencia de API de Aspose.Slides para C++
description: Iterador de diccionario que proporciona notación KeyValuePair.
type: docs
weight: 157
url: /es/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator clase


[Dictionary](../dictionary/) iterador que proporciona [KeyValuePair](../keyvaluepair/) notación.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Dict | [Dictionary](../dictionary/) clase. |
## Métodos

| Método | Descripción |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | Clona el iterador actual. |
| void [DecrementIterator](./decrementiterator/)() override | Mueve el iterador un paso atrás. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructor. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructor. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | Constructor de movimiento. |
| void [IncrementIterator](./incrementiterator/)() override | Mueve el iterador un paso adelante. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Mueve el iterador por el número especificado de pasos. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | Destructor. |

## Ver también

* Espacio de nombres [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)