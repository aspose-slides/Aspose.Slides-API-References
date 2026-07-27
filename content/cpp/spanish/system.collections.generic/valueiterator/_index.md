---
title: ValueIterator
second_title: Referencia de API de Aspose.Slides para C++
description: Iterador de diccionario que proporciona acceso a los valores.
type: docs
weight: 625
url: /es/system.collections.generic/valueiterator/
---
## ValueIterator clase

[Dictionary](../dictionary/) iterador que proporciona acceso a valores.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Dict | [Dictionary](../dictionary/) clase. |

## Métodos

| Método | Descripción |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | Clona el iterador actual. |
| void [DecrementIterator](./decrementiterator/)() override | Mueve el iterador un paso atrás. |
| void [IncrementIterator](./incrementiterator/)() override | Mueve el iterador un paso adelante. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Mueve el iterador la cantidad especificada de pasos. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructor. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructor. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | Constructor de movimiento. |
| virtual  [~ValueIterator](./~valueiterator/)() | Destructor. |

## Ver también

* Espacio de nombres [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)