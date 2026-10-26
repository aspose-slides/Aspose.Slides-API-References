---
title: Trim()
second_title: Referencia de la API de Aspose.Slides para C++
description: Elimina todos los caracteres de espacio en blanco del principio y del final de la cadena.
type: docs
weight: 677
url: /es/system/string/trim/
---
## String::Trim() const método

Elimina todos los caracteres de espacio en blanco del principio y del final de la cadena.

```cpp
String System::String::Trim() const
```

### Valor devuelto

[String](../) sin espacios en blanco al principio o al final.

## String::Trim(char_t) const método

Elimina todas las ocurrencias del carácter pasado del principio y del final de la cadena.

```cpp
String System::String::Trim(char_t ch) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ch | char_t | Símbolo a eliminar. |

### Valor devuelto

Resultado de la eliminación.

## String::Trim(const String\&) const método

Elimina todas las ocurrencias de los caracteres pasados del principio y del final de la cadena.

```cpp
String System::String::Trim(const String &anyOf) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) de caracteres a eliminar. |

### Valor devuelto

[String](../) sin caracteres eliminados.

## String::Trim(const ArrayPtr\<char_t\>\&) const método

Elimina todas las ocurrencias de los caracteres pasados del principio y del final de la cadena.

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a eliminar. |

### Valor devuelto

[String](../) sin caracteres eliminados.

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [String](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)