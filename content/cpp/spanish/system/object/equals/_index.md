---
title: Equals()
second_title: Referencia de API de Aspose.Slides para C++
description: Compara objetos usando la semántica de C# Object.Equals.
type: docs
weight: 157
url: /es/system/object/equals/
---
## Object::Equals(ptr) método


Compara objetos usando la semántica de C# [Object.Equals](./).

```cpp
virtual bool System::Object::Equals(ptr obj)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) para comparar con el actual. |

### Valor de retorno

True si los objetos son considerados iguales y false en caso contrario.

## Object::Equals(T1 const\&, T2 const\&) método


Compara objetos de tipo referencia al estilo C#.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del primer objeto a comparar. |
| T2 | Tipo del segundo objeto a comparar. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objA | T1 const\& | Primer objeto a comparar. |
| objB | T2 const\& | Segundo objeto a comparar. |

### Valor de retorno

True si los objetos coinciden ya sea por referencia o semánticamente (por comparación similar a [Object.Equals](./)), false en caso contrario.

## Object::Equals(T1 const\&, T2 const\&) método


Compara objetos de tipo valor al estilo C#.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del primer objeto a comparar. |
| T2 | Tipo del segundo objeto a comparar. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objA | T1 const\& | Primer objeto a comparar. |
| objB | T2 const\& | Segundo objeto a comparar. |

### Valor de retorno

True si los objetos se consideran iguales mediante el operador de igualdad disponible, false en caso contrario.

## Object::Equals(float const\&, float const\&) método


Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objA | **float** const\& | Valor de punto flotante del operando izquierdo. |
| objB | **float** const\& | Valor de punto flotante del operando derecho. |

### Valor de retorno

True si **objA** y **objB** son ambos NaN o iguales, false en caso contrario.

## Object::Equals(double const\&, double const\&) método


Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objA | **double** const\& | Valor de punto flotante del operando izquierdo. |
| objB | **double** const\& | Valor de punto flotante del operando derecho. |

### Valor de retorno

True si **objA** y **objB** son ambos NaN o iguales, false en caso contrario.

## Ver también

* Typedef [ptr](../ptr/)
* Clase [Object](../)
* Estructura [IsSmartPtr](../../issmartptr/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)