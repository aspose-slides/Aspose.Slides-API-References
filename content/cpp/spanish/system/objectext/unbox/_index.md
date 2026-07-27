---
title: Unbox()
second_title: Referencia de API de Aspose.Slides para C++
description: Desempaqueta tipos de valor después de convertir a Object. Implementación para tipos enum.
type: docs
weight: 53
url: /es/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) método


Desempaqueta tipos de valor después de convertir a [Object](../../object/). Implementación para tipos enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | [Enum](../../enum/) type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) para desempaquetar. |

### Valor devuelto

[Enum](../../enum/) valor.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) método


Desempaqueta tipos de valor después de convertir a [Object](../../object/). Implementación para tipos que no son enum y no son anulables.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Value type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) para desempaquetar. |

### Valor devuelto

Valor desempaquetado.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) método


Desempaqueta tipos de valor después de convertir a [Object](../../object/). Implementación para tipos que no son enum y no son anulables.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Value type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) para desempaquetar. |

### Valor devuelto

Valor desempaquetado.

## ObjectExt::Unbox(E) método


Desempaqueta tipos enum a entero.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Destination integer type. |
| E | Source enum type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| e | E | Value to unbox. |

### Valor devuelto

Representación entera del enum.

## ObjectExt::Unbox(E) método


Convierte tipos enum.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Destination enum type. |
| E | Source enum type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| e | E | Value to unbox. |

### Valor devuelto

Valor de enum convertido.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) método


Desempaqueta valores de cadena.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) para desempaquetar |

### Valor devuelto

[String](../../string/) representación de cadena empaquetada, puede ser nula si la cadena empaquetada era nula.

## Véase también

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Class [String](../../string/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)