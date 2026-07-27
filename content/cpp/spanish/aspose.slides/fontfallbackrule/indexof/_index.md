---
title: IndexOf()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve un índice de la regla especificada en la colección.
type: docs
weight: 157
url: /es/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) método

Devuelve un índice de la regla especificada en la colección.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nombre de la fuente a buscar. |

### Valor de retorno

Índice de una fuente o -1 si la fuente no se encuentra en la lista.

## Observaciones



```cpp
// Crear una regla que contiene una lista de fuentes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Obtener el índice de Tahoma.
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## Véase también

* Clase [String](../../../system/string/)
* Clase [FontFallBackRule](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)