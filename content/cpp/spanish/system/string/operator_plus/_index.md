---
title: operator+()
second_title: Referencia de API de Aspose.Slides para C++
description: Operador de concatenación de cadenas.
type: docs
weight: 274
url: /es/system/string/operator_plus/
---
## String::operator+(const String\&) const method


[String](../) operador de concatenación.

```cpp
String System::String::operator+(const String &str) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) para agregar al final del actual. |

### Valor devuelto

Cadena concatenada.

## String::operator+(const T\&) const method


[String](../) concatenación con literal de cadena o puntero a cadena de caracteres.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Una de las formas de literal de cadena o puntero a cadena de caracteres. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg | const T\& | Entidad para concatenar con la cadena actual. |

### Valor devuelto

Cadena concatenada.

## String::operator+(char_t) const method


Agrega un carácter al final de la cadena.

```cpp
String System::String::operator+(char_t x) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | char_t | Carácter a agregar. |

### Valor devuelto

[String](../) resultado de concatenación.

## String::operator+(int) const method


Agrega la representación en cadena del valor entero al final de la cadena.

```cpp
String System::String::operator+(int i) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | int | Valor entero para convertir a cadena y agregar. |

### Valor devuelto

[String](../) resultado de concatenación.

## String::operator+(uint32_t) const method


Agrega la representación en cadena del valor entero sin signo al final de la cadena.

```cpp
String System::String::operator+(uint32_t i) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | **uint32_t** | Valor para convertir a cadena y agregar. |

### Valor devuelto

[String](../) resultado de concatenación.

## String::operator+(double) const method


Agrega la representación en cadena del valor de punto flotante al final de la cadena.

```cpp
String System::String::operator+(double d) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| d | **double** | Valor para convertir a cadena y agregar. |

### Valor devuelto

[String](../) resultado de concatenación.

## String::operator+(int64_t) const method


Agrega la representación en cadena del valor entero al final de la cadena.

```cpp
String System::String::operator+(int64_t v) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v | **int64_t** | Valor para convertir a cadena y agregar. |

### Valor devuelto

[String](../) resultado de concatenación.

## String::operator+(const T\&) const method


Agrega la representación en cadena del objeto de tipo referencia al final de la cadena.

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de puntero. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) para convertir a cadena usando la llamada [ToString()](../tostring/) y agregar a la cadena actual. |

### Valor devuelto

[String](../) resultado de concatenación.

## String::operator+(const T\&) const method


Agrega la representación en cadena del objeto de tipo valor al final de la cadena.

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de valor para llamar a [ToString()](../tostring/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) para convertir a cadena usando la llamada [ToString()](../tostring/) y agregar a la cadena actual. |

### Valor devuelto

[String](../) resultado de concatenación.

## String::operator+(T) const method


Agrega la representación en cadena del valor booleano al final de la cadena.

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de valor para concatenar con la cadena. Debe ser bool |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) valor para convertir a cadena y agregar. |

### Valor devuelto

[String](../) resultado de concatenación.

## Ver también

* Clase [String](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)