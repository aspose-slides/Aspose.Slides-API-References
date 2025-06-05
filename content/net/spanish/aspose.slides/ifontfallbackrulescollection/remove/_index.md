---
title: Remove
second_title: Aspose.Sildes para .NET Referencia de API
description: Elimina la primera ocurrencia de una regla FallBack específica de la colección.
type: docs
weight: 30
url: /es/aspose.slides/ifontfallbackrulescollection/remove/
---

## IFontFallBackRulesCollection.Remove método

Elimina la primera ocurrencia de una regla FallBack específica de la colección.

```csharp
public void Remove(IFontFallBackRule targetRule)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetRule | IFontFallBackRule | La regla a eliminar de la colección. |

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation ())
{
    //Obtención de la colección de reglas vacía o preinicializada de FontsManager
    IFontFallBackRulesCollection rulesList = pres.FontsManager.FontFallBackRulesCollection;

    //Adición de varias reglas a la colección
    rulesList.Add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
    rulesList.Add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));

    //Recuperación del objeto de la primera regla en la colección
    IFontFallBackRule firstRule = rulesList[0];
    //Eliminando 
    rulesList.Remove (firstRule);
}
```

### Véase También

* interfaz [IFontFallBackRule](../../ifontfallbackrule)
* interfaz [IFontFallBackRulesCollection](../../ifontfallbackrulescollection)
* espacio de nombres [Aspose.Slides](../../ifontfallbackrulescollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->