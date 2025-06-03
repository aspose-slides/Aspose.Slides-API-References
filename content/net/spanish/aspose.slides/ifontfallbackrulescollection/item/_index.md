---
title: Item
second_title: Referencia de la API de Aspose.Slides para .NET
description: Obtiene la regla en el índice especificado. Solo lectura IFontFallBackRuleaspose.slides/ifontfallbackrule.
type: docs
weight: 10
url: /es/aspose.slides/ifontfallbackrulescollection/item/
---

## Indexador de IFontFallBackRulesCollection

Obtiene la regla en el índice especificado. Solo lectura [`IFontFallBackRule`](../../ifontfallbackrule).

```csharp
public IFontFallBackRule this[int index] { get; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation ())
{
    //Obteniendo colección de reglas vacía o preinicializada desde FontsManager
    IFontFallBackRulesCollection rulesList = pres.FontsManager.FontFallBackRulesCollection;

    //Agregando varias reglas a la colección
    rulesList.Add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
    rulesList.Add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));

    //Recuperando el objeto de la primera regla en la colección
    IFontFallBackRule firstRule = rulesList[0];
}
```

### Vea también

* interfaz [IFontFallBackRule](../../ifontfallbackrule)
* interfaz [IFontFallBackRulesCollection](../../ifontfallbackrulescollection)
* espacio de nombres [Aspose.Slides](../../ifontfallbackrulescollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->