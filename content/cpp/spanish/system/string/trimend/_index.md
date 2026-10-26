---
title: TrimEnd()
second_title: Referencia de la API de Aspose.Slides para C++
description: Elimina todos los caracteres de espacio en blanco del final de la cadena.
type: docs
weight: 703
url: /es/system/string/trimend/
---
## String::TrimEnd() const método


Elimina todos los caracteres de espacio en blanco del final de la cadena.

```cpp
String System::String::TrimEnd() const
```


### Valor de retorno

[String](../) sin espacios en blanco al principio.

## String::TrimEnd(char_t) const método


Elimina todas las apariciones del carácter pasado del final de la cadena.

```cpp
String System::String::TrimEnd(char_t ch) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ch | char_t | Símbolo a eliminar. |

### Valor de retorno

Resultado de la eliminación.

## String::TrimEnd(const String\&) const método


Elimina todas las apariciones de los caracteres pasados del final de la cadena.

```cpp
String System::String::TrimEnd(const String &anyOf) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) de caracteres a eliminar. |

### Valor de retorno

[String](../) sin caracteres eliminados.

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const método


Elimina todas las apariciones de los caracteres pasados del final de la cadena.

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a eliminar. |

### Valor de retorno

[String](../) sin caracteres eliminados.

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [String](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)