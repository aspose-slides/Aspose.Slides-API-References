---
title: TrimStart()
second_title: Referencia de API de Aspose.Slides para C++
description: Elimina todos los caracteres de espacio en blanco al inicio de la cadena.
type: docs
weight: 690
url: /es/system/string/trimstart/
---
## String::TrimStart() const method

Elimina todos los caracteres de espacio en blanco al inicio de la cadena.

```cpp
String System::String::TrimStart() const
```

### Valor de retorno

[String](../) sin espacios en blanco al inicio.

## String::TrimStart(char_t) const method

Elimina todas las ocurrencias del carácter pasado al inicio de la cadena.

```cpp
String System::String::TrimStart(char_t ch) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ch | char_t | Símbolo a eliminar. |

### Valor de retorno

Resultado de la eliminación.

## String::TrimStart(const String\&) const method

Elimina todas las ocurrencias de los caracteres pasados al inicio de la cadena.

```cpp
String System::String::TrimStart(const String &anyOf) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) de caracteres a eliminar. |

### Valor de retorno

[String](../) sin los caracteres eliminados.

## String::TrimStart(const ArrayPtr\<char_t\>\&) const method

Elimina todas las ocurrencias de los caracteres pasados al inicio de la cadena.

```cpp
String System::String::TrimStart(const ArrayPtr<char_t> &anyOf) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a eliminar. |

### Valor de retorno

[String](../) sin los caracteres eliminados.

## Véase también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [String](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)