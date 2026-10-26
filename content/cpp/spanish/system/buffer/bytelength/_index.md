---
title: ByteLength()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina el número de bytes ocupados por todos los elementos del arreglo especificado.
type: docs
weight: 14
url: /es/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) método

Determina el número de bytes ocupados por todos los elementos del arreglo especificado.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos del arreglo |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Un arreglo |

### Valor de retorno

El número de bytes ocupados por todos los elementos del arreglo especificado

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) método

Determina el número de bytes ocupados por todos los elementos de la vista de arreglo especificada.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos de la vista de arreglo |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Una vista de arreglo |

### Valor de retorno

El número de bytes ocupados por todos los elementos de la vista de arreglo especificada

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) método

Determina el número de bytes ocupados por todos los elementos del arreglo de pila especificado.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos del arreglo de pila |
| N | El tamaño del arreglo de pila |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Un arreglo de pila |

### Valor de retorno

El número de bytes ocupados por todos los elementos del arreglo de pila especificado

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)