---
title: Equals()
second_title: Referencia de API de Aspose.Slides para C++
description: 
type: docs
weight: 14
url: /es/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) method




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) method


Sustitución de llamadas C# [Object.Equals](../../object/equals/) que funcionan para cualquier tipo en C++. Sobrecarga para tipos de punteros inteligentes.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del primer objeto. |
| T2 | Tipo del segundo objeto. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | Primer objeto. |
| another | const T2\& | Segundo objeto. |

### Valor de retorno

True si los objetos se consideran iguales, false en caso contrario.

## ObjectExt::Equals(T, const T2\&) method


Sustitución de llamadas C# [Object.Equals](../../object/equals/) que funcionan para cualquier tipo en C++. Sobrecarga para tipos de estructura.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del primer objeto. |
| T2 | Tipo del segundo objeto. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T | Primer objeto. |
| another | const T2\& | Segundo objeto. |

### Valor de retorno

True si los objetos se consideran iguales, false en caso contrario.

## ObjectExt::Equals(const T\&, const T2\&) method


Sustitución de llamadas C# [Object.Equals](../../object/equals/) que funcionan para cualquier tipo en C++. Sobrecarga para tipos escalares.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del primer objeto. |
| T2 | Tipo del segundo objeto. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | Primer objeto. |
| another | const T2\& | Segundo objeto. |

### Valor de retorno

True si los objetos se consideran iguales, false en caso contrario.

## ObjectExt::Equals(const char_t(&), String) method


Sustitución de llamadas C# [Object.Equals](../../object/equals/) que funcionan para cualquier tipo en C++. Sobrecarga para literal de cadena con comparación de cadenas.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| N | [String](../../string/) tamaño del literal. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) literal. |
| another | [String](../../string/) | [String](../../string/). |

### Valor de retorno

True si las cadenas coinciden, false en caso contrario.

## ObjectExt::Equals(const float\&, const float\&) method


Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const **float**\& | Valor de punto flotante del LHS. |
| another | const **float**\& | Valor de punto flotante del RHS. |

### Valor de retorno

True si **obj** y **another** son ambos NaN o iguales, false en caso contrario.

## ObjectExt::Equals(const double\&, const double\&) method


Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const **double**\& | Valor de punto flotante del LHS. |
| another | const **double**\& | Valor de punto flotante del RHS. |

### Valor de retorno

True si **obj** y **another** son ambos NaN o iguales, false en caso contrario.

## See Also

* Class [ObjectExt](../)
* Class [String](../../string/)
* Struct [IsExceptionWrapper](../../isexceptionwrapper/)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)