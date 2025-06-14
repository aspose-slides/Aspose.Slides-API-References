---
title: FontSubstitutionInfo
second_title: Referencia de API de Aspose.Slides para .NET
description: Esta estructura representa la información sobre el reemplazo de fuentes cuando se va a renderizar.
type: docs
weight: 4710
url: /es/aspose.slides/fontsubstitutioninfo/
---

## Clase FontSubstitutionInfo

Esta estructura representa la información sobre el reemplazo de fuentes cuando se va a renderizar.

```csharp
public class FontSubstitutionInfo
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FontSubstitutionInfo](fontsubstitutioninfo)(string, string) | Crea una instancia de la clase [`FontSubstitutionInfo`](../fontsubstitutioninfo). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [OriginalFontName](../../aspose.slides/fontsubstitutioninfo/originalfontname) { get; } | Indica el nombre de la fuente original en la presentación. Cadena de solo lectura |
| [SubstitutedFontName](../../aspose.slides/fontsubstitutioninfo/substitutedfontname) { get; } | Indica el nombre de la fuente de reemplazo para la fuente original. Cadena de solo lectura |

### Ejemplos

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    foreach (FontSubstitutionInfo fontSubstitution in pres.FontsManager.GetSubstitutions())
    {
        Console.WriteLine("{0} -> {1}", fontSubstitution.OriginalFontName, fontSubstitution.SubstitutedFontName);
    }
}        
```

### Ver también

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->