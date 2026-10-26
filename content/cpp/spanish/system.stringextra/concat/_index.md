---
title: Concat()
second_title: Referencia de API de Aspose.Slides para C++
description: Concatena un array de cadenas.
type: docs
weight: 1
url: /es/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) función


Concatena un array de cadenas.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) de cadenas a unir. |

### Valor devuelto

Cadena concatenada.

## System::StringExtra::Concat(const String\&, const String\&) función


Concatena cadenas.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Primera cadena a concatenar. |
| str1 | const [String](../../system/string/)\& | Segunda cadena a concatenar. |

### Valor devuelto

Cadenas de parámetros concatenadas.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) función


Concatena cadenas.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Primera cadena a concatenar. |
| str1 | const [String](../../system/string/)\& | Segunda cadena a concatenar. |
| str2 | const [String](../../system/string/)\& | Tercera cadena a concatenar. |

### Valor devuelto

Cadenas de parámetros concatenadas.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) función


Concatena cadenas.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Primera cadena a concatenar. |
| str1 | const [String](../../system/string/)\& | Segunda cadena a concatenar. |
| str2 | const [String](../../system/string/)\& | Tercera cadena a concatenar. |
| str3 | const [String](../../system/string/)\& | Cuarta cadena a concatenar. |

### Valor devuelto

Cadenas de parámetros concatenadas.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) función


Convierte varios objetos a cadena y concatena las cadenas resultantes. Especialización para tipos [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) para convertir y unir. |

### Valor devuelto

valor [String](../../system/string/) concatenado a partir de representaciones en cadena de todos los objetos pasados.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) función


Convierte varios objetos a cadena y concatena las cadenas resultantes. Especialización para tipos aritméticos.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) para convertir y unir. |

### Valor devuelto

valor [String](../../system/string/) concatenado a partir de representaciones en cadena de todos los objetos pasados.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) función


Convierte varios objetos a cadena y concatena las cadenas resultantes. Especialización para estructuras y otros tipos de valor.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) para convertir y unir. |

### Valor devuelto

valor [String](../../system/string/) concatenado a partir de representaciones en cadena de todos los objetos pasados.

## Ver también

* Typedef [ArrayPtr](../../system/arrayptr/)
* Clase [String](../../system/string/)
* Estructura [IsSmartPtr](../../system/issmartptr/)
* Espacio de nombres [System::StringExtra](../)
* Biblioteca [Aspose.Slides](../../)