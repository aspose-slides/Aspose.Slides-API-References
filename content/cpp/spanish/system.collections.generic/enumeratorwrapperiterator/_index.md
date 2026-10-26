---
title: EnumeratorWrapperIterator
second_title: Referencia de API de Aspose.Slides para C++
description: Iterador que envuelve el enumerador precreado y redirige todas las llamadas a él.
type: docs
weight: 196
url: /es/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator clase

Iterador que envuelve el enumerador precreado y redirige todas las llamadas a él.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Element | Element type. |

## Métodos

| Método | Descripción |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Clona el iterador actual. |
| [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | Avanza el iterador un paso. Debe actualizar m_is_end y m_pointer. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | Comprueba si dos iteradores apuntan al mismo elemento. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Destructor. |

## Véase también

* Espacio de nombres [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)