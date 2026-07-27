---
title: IndexOf()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve un índice de la regla especificada en la colección.
type: docs
weight: 118
url: /es/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) método

Devuelve un índice de la regla especificada en la colección.

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nombre de la fuente a buscar. |

### Valor devuelto

Índice de una fuente o -1 si la fuente no se encuentra en la lista.

## Comentarios

```cpp
// Crear una regla que contiene una lista de fuentes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Obtener el índice de Tahoma
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [IFontFallBackRule](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)