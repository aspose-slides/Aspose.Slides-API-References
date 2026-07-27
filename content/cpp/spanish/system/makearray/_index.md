---
title: MakeArray()
second_title: Referencia de API de Aspose.Slides para C++
description: Una función de fábrica que construye un nuevo objeto Array, lo llena con los elementos de la lista de inicialización especificada y devuelve un puntero inteligente que apunta al objeto Array.
type: docs
weight: 2029
url: /es/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) función


Una función de fábrica que construye un nuevo objeto [Array](../array/), lo llena con los elementos de la lista de inicialización especificada y devuelve un puntero inteligente que apunta al objeto [Array](../array/).

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos del objeto [Array](../array/) que la función construye |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| init | std::initializer_list\<T\> | La lista de inicialización que contiene los elementos con los que se llenará el arreglo |

### Valor de retorno

Un puntero inteligente que apunta al objeto [Array](../array/) construido

## System::MakeArray(Args\&&...) función


Una función de fábrica que construye un nuevo objeto [Array](../array/) pasando los argumentos especificados a su constructor.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos del objeto [Array](../array/) que la función construye |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | Args\&&... | Los argumentos que se pasan al constructor del objeto [Array](../array/) que se está construyendo |

### Valor de retorno

Un puntero inteligente que apunta al objeto [Array](../array/) construido

## System::MakeArray(Integral, Args\&&...) función


Una función de fábrica que construye un nuevo objeto [Array](../array/) pasando los argumentos especificados a su constructor.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos del objeto [Array](../array/) que la función construye |
| Integral | Tipo del tamaño del arreglo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | Integral | Tamaño del arreglo que se está creando. |
| args | Args\&&... | Los argumentos que se pasan al constructor del objeto [Array](../array/) que se está construyendo |

### Valor de retorno

Un puntero inteligente que apunta al objeto [Array](../array/) construido

## Véase también

* Typedef [ArrayPtr](../arrayptr/)
* Espacio de nombres [System](../)
* Library [Aspose.Slides](../../)