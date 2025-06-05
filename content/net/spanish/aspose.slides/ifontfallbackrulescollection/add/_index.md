---
title: Add
second_title: Referencia de la API de Aspose.Slides para .NET
description: Agregar una nueva regla FallBack al final de la colección.
type: docs
weight: 20
url: /es/aspose.slides/ifontfallbackrulescollection/add/
---

## IFontFallBackRulesCollection.Add método

Agregar una nueva regla FallBack al final de la colección.

```csharp
public void Add(IFontFallBackRule sourceRule)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceRule | IFontFallBackRule | Regla especificada para agregar |

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation ())
{
    //Obtención de una colección de reglas vacía o preinicializada del FontsManager
    IFontFallBackRulesCollection rulesList = pres.FontsManager.FontFallBackRulesCollection;

    //Adición de una nueva regla a la colección
    rulesList.Add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
}
```

### Véase también

* interfaz [IFontFallBackRule](../../ifontfallbackrule)
* interfaz [IFontFallBackRulesCollection](../../ifontfallbackrulescollection)
* espacio de nombres [Aspose.Slides](../../ifontfallbackrulescollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->