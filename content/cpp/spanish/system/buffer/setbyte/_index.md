---
title: SetByte()
second_title: Referencia de la API de Aspose.Slides para C++
description: Interpreta la matriz tipada especificada como una matriz de bytes cruda y establece el valor de byte especificado en el desplazamiento de byte especificado.
type: docs
weight: 40
url: /es/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) método


Interpreta la matriz tipada especificada como una matriz de bytes cruda y establece el valor de byte especificado en el desplazamiento de byte especificado.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos de la matriz |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | La matriz objetivo |
| index | int | Desplazamiento basado en cero del byte a establecer |
| value | **uint8_t** | El valor de byte a establecer |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) método


Interpreta la matriz tipada especificada como una matriz de bytes cruda y establece el valor de byte especificado en el desplazamiento de byte especificado.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos de la matriz |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | La vista de matriz objetivo |
| index | int | Desplazamiento basado en cero del byte a establecer |
| value | **uint8_t** | El valor de byte a establecer |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) método


Interpreta la matriz tipada especificada como una matriz de bytes cruda y establece el valor de byte especificado en el desplazamiento de byte especificado.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos de la matriz |
| N | El tamaño de la matriz de pila |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | La matriz de pila objetivo |
| index | int | Desplazamiento basado en cero del byte a establecer |
| value | **uint8_t** | El valor de byte a establecer |

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [Array](../../array/)
* Clase [Buffer](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)