---
title: Ítem
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene la regla en el índice especificado. Solo lectura IFontFallBackRuleaspose.slides/ifontfallbackrule.
type: docs
weight: 40
url: /es/aspose.slides/fontfallbackrulescollection/item/
---

## Indexador FontFallBackRulesCollection

Obtiene la regla en el índice especificado. Solo lectura [`IFontFallBackRule`](../../ifontfallbackrule).

```csharp
public IFontFallBackRule this[int index] { get; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation ())
{
    //Obtención de una colección de reglas vacía o preinicializada del FontsManager
    IFontFallBackRulesCollection rulesList = pres.FontsManager.FontFallBackRulesCollection;

    //Adición de varias reglas a la colección
    rulesList.Add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
    rulesList.Add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));

    //Recuperación del objeto de la primera regla en la colección
    IFontFallBackRule firstRule = rulesList[0];
}
```

### Ver También

* interfaz [IFontFallBackRule](../../ifontfallbackrule)
* clase [FontFallBackRulesCollection](../../fontfallbackrulescollection)
* namespace [Aspose.Slides](../../fontfallbackrulescollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->