---
title: GetHashCode()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve un código hash para el valor escalar especificado.
type: docs
weight: 2484
url: /es/system/gethashcode/
---
## System::GetHashCode(const T\&) función


Devuelve un código hash para el valor escalar especificado.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo del valor para el cual la función genera el código hash |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | El valor para el cual generar el código hash |

### Valor devuelto

El código hash generado para el valor especificado

## System::GetHashCode(const T\&) función


Devuelve un código hash para el objeto especificado.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto para el cual la función genera el código hash |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | El [SmartPtr](../smartptr/) que apunta al objeto para generar el código hash |

### Valor devuelto

El código hash generado para el objeto especificado

## System::GetHashCode(const T\&) función


Devuelve un código hash para el objeto especificado que es una excepción.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto para el cual la función genera el código hash |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | El Exception Wrapper que contiene el objeto para generar el código hash |

### Valor devuelto

El código hash generado para el objeto especificado

## System::GetHashCode(const T\&) función


Devuelve un código hash para el objeto especificado que no es un puntero inteligente ni una excepción.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto para el cual la función genera el código hash |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | Una referencia constante al objeto para generar el código hash |

### Valor devuelto

El código hash generado para el objeto especificado

## System::GetHashCode(const std::thread::id\&) función


Especialización para std::thread::id; Devuelve el código hash para el objeto de hilo especificado.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## Ver también

* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)