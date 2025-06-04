---
title: GetSubstitutions
second_title: Aspose.Slides para .NET Referencia de API
description: Obtiene la información sobre las fuentes que serán reemplazadas en el renderizado de las presentaciones.
type: docs
weight: 80
url: /es/aspose.slides/ifontsmanager/getsubstitutions/
---

## IFontsManager.GetSubstitutions método

Obtiene la información sobre las fuentes que serán reemplazadas en el renderizado de la presentación.

```csharp
public IEnumerable<FontSubstitutionInfo> GetSubstitutions()
```

### Valor de Retorno

Colección de todos los reemplazos de fuentes [`FontSubstitutionInfo`](../../fontsubstitutioninfo).

### Ejemplos

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    foreach (var fontSubstitution in pres.FontsManager.GetSubstitutions())
    {
        Console.WriteLine("{0} -> {1}", fontSubstitution.OriginalFontName, fontSubstitution.SubstitutedFontName);
    }
}        
```

### Véase También

* class [FontSubstitutionInfo](../../fontsubstitutioninfo)
* interface [IFontsManager](../../ifontsmanager)
* namespace [Aspose.Slides](../../ifontsmanager)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->