---
title: Colección deReglasFontFallBack
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa una colección de reglas FontFallBack del usuario para gestionar conjuntos de fuentes para sustituciones adecuadas mediante la funcionalidad de respaldo. Lectura/escritura IFontFallBackRulesCollectionaspose.slides/ifontfallbackrulescollection.
type: docs
weight: 10
url: /es/aspose.slides/fontsmanager/fontfallbackrulescollection/
---

## Propiedad FontsManager.FontFallBackRulesCollection

Representa una colección de reglas FontFallBack del usuario para gestionar conjuntos de fuentes para sustituciones adecuadas mediante la funcionalidad de respaldo. Lectura/escritura [`IFontFallBackRulesCollection`](../../ifontfallbackrulescollection).

```csharp
public IFontFallBackRulesCollection FontFallBackRulesCollection { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation ())
{
    // Obtención de una colección de reglas vacía o preinicializada del FontsManager
    IFontFallBackRulesCollection rulesList = pres.FontsManager.FontFallBackRulesCollection;

    // añadiendo reglas a la colección
    rulesList.Add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));

    // o 
    // inicialización de una nueva instancia de la colección de reglas
    IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();

    // añadiendo reglas a la colección
    rulesList.Add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));

    // y reemplazando la colección existente por la nueva en FontsManager 
    pres.FontsManager.FontFallBackRulesCollection = rulesList;
}
```

### Ver También

* interfaz [IFontFallBackRulesCollection](../../ifontfallbackrulescollection)
* clase [FontsManager](../../fontsmanager)
* espacio de nombres [Aspose.Slides](../../fontsmanager)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->