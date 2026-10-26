---
title: Insert()
second_title: Referencia de API de Aspose.Slides para C++
description: Inserta una cadena en la posición fija del constructor.
type: docs
weight: 183
url: /es/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) método

Inserta una cadena en la posición fija del constructor.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int | Posición donde insertar los caracteres. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) para insertar. |

### Valor devuelto

Este puntero.

## StringBuilder::Insert(int32_t, const String\&, int32_t) método

Inserta una cadena repetida en la posición fija del constructor.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Posición donde insertar los caracteres. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) para insertar. |
| count | **int32_t** | Cuántas veces repetir la cadena **value**. |

### Valor devuelto

Este puntero.

## StringBuilder::Insert(int, char_t) método

Inserta un carácter en la posición fija del constructor.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int | Posición donde insertar los caracteres. |
| ch | char_t | Carácter a insertar. |

### Valor devuelto

Este puntero.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) método

Inserta caracteres en la posición fija del constructor.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Posición donde insertar los caracteres. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) para insertar una porción de. |
| startIndex | int | [Array](../../../system/array/) índice de comienzo de la porción. |
| charCount | int | [Array](../../../system/array/) longitud de la porción. |

### Valor devuelto

Este puntero.

## StringBuilder::Insert(int, T) método

Inserta un valor en la posición fija del constructor.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Parameter | tipo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int | Posición donde insertar los caracteres. |
| value | T | Valor a formatear e insertar. |

### Valor devuelto

Este puntero.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [StringBuilder](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Text](../../)
* Library [Aspose.Slides](../../../)