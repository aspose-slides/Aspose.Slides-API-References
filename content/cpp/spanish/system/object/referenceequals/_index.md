---
title: ReferenceEquals()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Especialización de Object::ReferenceEquals para el caso de string y nullptr."
type: docs
weight: 261
url: /es/system/object/referenceequals/
---
## Object::ReferenceEquals(String const&, std::nullptr_t) método


Especialización de [Object::ReferenceEquals](./) para el caso de string y nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | [String](../../string/) const& | [String](../../string/) para comparar con nullptr. |

### Valor de retorno

true si la cadena es nula, false en caso contrario.

## Object::ReferenceEquals(String const&, String const&) método


Especialización de [Object::ReferenceEquals](./) para el caso de strings.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str1 | [String](../../string/) const& | Primera cadena a comparar. |
| str2 | [String](../../string/) const& | Segunda cadena a comparar. |

### Valor de retorno

true si las cadenas coinciden, false en caso contrario.

## Object::ReferenceEquals(ptr const&, ptr const&) método


Compara objetos por referencia.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objA | [ptr](../ptr/) const& | Primer puntero a comparar. |
| objB | [ptr](../ptr/) const& | Segundo puntero a comparar. |

### Valor de retorno

True si los punteros coinciden y false en caso contrario.

## Object::ReferenceEquals(T const&, T const&) método


Compara objetos por referencia.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objetos a comparar. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objA | T const& | Primer objeto a comparar. |
| objB | T const& | Segundo objeto a comparar. |

### Valor de retorno

True si las direcciones de los objetos coinciden y false en caso contrario.

## Object::ReferenceEquals(T const&, std::nullptr_t) método


Compara por referencia un objeto de tipo valor con nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objeto a comparar. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objA | T const& | Primer objeto a comparar. |

### Valor de retorno

Siempre devuelve false ya que los tipos valor no pueden ser nulos.

## Ver también

* Typedef [ptr](../ptr/)
* Class [String](../../string/)
* Class [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)