---
title: KeyIterator
second_title: Referencia de la API de Aspose.Slides para C++
description: Iterador de diccionario que proporciona acceso a claves.
type: docs
weight: 365
url: /es/system.collections.generic/keyiterator/
---
## KeyIterator clase


[Dictionary](../dictionary/) iterador que proporciona acceso a claves.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Dict | [Dictionary](../dictionary/) clase. |
## Métodos

| Método | Descripción |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | Clona el iterador actual. |
| void [DecrementIterator](./decrementiterator/)() override | Mueve el iterador un paso atrás. |
| void [IncrementIterator](./incrementiterator/)() override | Mueve el iterador un paso adelante. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructor. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructor. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | Constructor de movimiento. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Mueve el iterador la cantidad especificada de pasos. |
| virtual  [~KeyIterator](./~keyiterator/)() | Destructor. |

## Ver también

* Espacio de nombres [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)