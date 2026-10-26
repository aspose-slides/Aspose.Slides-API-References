---
title: Array()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye un array vacío.
type: docs
weight: 1
url: /es/system/array/array/
---
## Array::Array() constructor


Construye un array vacío.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) constructor


Constructor de rellenado.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| count | int | Tamaño inicial del array |
| init | const T\& | El valor inicial utilizado para rellenar el array |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) constructor


Constructor de rellenado.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ValueType | Tipo del valor inicial |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | Tamaño inicial del array |
| init | [ValueType](../valuetype/) | El valor inicial utilizado para rellenar el array |

## Array::Array(int, const T) constructor


Constructor de rellenado.

```cpp
System::Array<T>::Array(int count, const T inits[])
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| count | int | Tamaño inicial del array |
| inits | const T | Valores para rellenar el array |

## Array::Array(vector_t\&&) constructor


Constructor de movimiento.

```cpp
System::Array<T>::Array(vector_t &&value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector, cuyos elementos son adquiridos por el array |

## Array::Array(const vector_t\&) constructor


Constructor de copia.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| assgn | const **vector_t**\& | std::vector del que se copian los valores |

## Array::Array(const std::vector\<Q\>\&) constructor


Construye un objeto [Array](../) y lo rellena con valores copiados de un objeto std::vector cuyo tipo de valores es el mismo que **T** pero distinto de **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Q | El tipo de los elementos del objeto std::vector del que se copian los elementos |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector del que se copian los valores |

## Array::Array(std::vector\<Q\>\&&) constructor


Construye un objeto [Array](../) y lo rellena con valores movidos de un objeto std::vector cuyo tipo de valores es el mismo que **T** pero distinto de **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Q | El tipo de los elementos del objeto std::vector del que se mueven los elementos |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector del que se copian los valores |

## Array::Array(std::initializer_list\<UnderlyingType\>) constructor


Construye un objeto [Array](../) y lo rellena con valores de la lista de inicialización especificada que contiene elementos del tipo **UnderlyingType**.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | Lista de inicialización que contiene los elementos para rellenar el array |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) constructor


Construye un objeto [Array](../) y lo rellena con valores del array especificado que contiene elementos del tipo **UnderlyingType**.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| InitArraySize | Número de elementos del array **init**. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) para copiar en el array que se está construyendo. |

## Array::Array(std::initializer_list\<bool\>, int) constructor


Construye un objeto [Array](../) y lo rellena con valores de la lista de inicialización especificada que contiene elementos del tipo bool.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | Lista de inicialización que contiene los elementos para rellenar el array |

## Véase también

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* Clase [Array](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)