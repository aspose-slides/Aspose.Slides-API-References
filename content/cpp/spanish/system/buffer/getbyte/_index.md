---
title: GetByte()
second_title: Referencia de API de Aspose.Slides para C++
description: Interpreta la matriz tipada especificada como una matriz de bytes cruda y recupera el valor del byte en el desplazamiento especificado.
type: docs
weight: 27
url: /es/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) method

Interpreta la matriz tipada especificada como una matriz de bytes cruda y recupera el valor del byte en el desplazamiento especificado.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos de la matriz |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | La matriz objetivo |
| index | int | Desplazamiento basado en cero del byte a recuperar |

### Valor de retorno

El valor del byte en el índice especificado

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) method

Interpreta la matriz tipada especificada como una matriz de bytes cruda y recupera el valor del byte en el desplazamiento especificado.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos de la vista de matriz |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | La vista de matriz objetivo |
| index | int | Desplazamiento basado en cero del byte a recuperar |

### Valor de retorno

El valor del byte en el índice especificado

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) method

Interpreta la matriz tipada especificada como una matriz de bytes cruda y recupera el valor del byte en el desplazamiento especificado.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos de la matriz de pila |
| N | El tamaño de la matriz de pila |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | La matriz de pila objetivo |
| index | int | Desplazamiento basado en cero del byte a recuperar |

### Valor de retorno

El valor del byte en el índice especificado

## Véase también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [Array](../../array/)
* Clase [Buffer](../)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)