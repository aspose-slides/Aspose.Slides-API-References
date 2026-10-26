---
title: TryParse()
second_title: Referencia de la API de Aspose.Slides para C++
description: Intenta convertir la cadena especificada en la constante enum equivalente.
type: docs
weight: 79
url: /es/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) método

Intenta convertir la cadena especificada en la constante enum equivalente.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) que se interpreta como que contiene el nombre de la constante enum |
| result | E\& | El parámetro de salida que, si la conversión tiene éxito, contiene el resultado de la conversión en la función |

### Valor de retorno

True si la conversión tuvo éxito, de lo contrario - false

## Enum::TryParse(const String\&, bool, E\&) método

Intenta convertir la cadena especificada en la constante enum equivalente.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) que se interpreta como que contiene el nombre de la constante enum |
| ignoreCase | **bool** | Especifica si se debe ignorar mayúsculas/minúsculas al interpretar la cadena |
| result | E\& | El parámetro de salida que, si la conversión tiene éxito, contiene el resultado de la conversión en el valor de retorno de la función |

### Valor de retorno

True si la conversión tuvo éxito, de lo contrario - false

## See Also

* Clase [String](../../string/)
* Estructura [Enum](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)