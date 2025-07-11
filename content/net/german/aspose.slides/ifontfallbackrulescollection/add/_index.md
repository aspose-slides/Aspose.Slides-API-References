---
title: Add
second_title: Aspose.Sildes für .NET API Referenz
description: Fügen Sie eine neue FallBack-Regel am Ende der Sammlung hinzu.
type: docs
weight: 20
url: /de/aspose.slides/ifontfallbackrulescollection/add/
---

## IFontFallBackRulesCollection.Add Methode

Fügen Sie eine neue FallBack-Regel am Ende der Sammlung hinzu.

```csharp
public void Add(IFontFallBackRule sourceRule)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceRule | IFontFallBackRule | Angegebene Regel zum Hinzufügen |

### Beispiele

```csharp
[C#]
using (Presentation pres = new Presentation ())
{
    //Erhalten der leeren oder vorinitialisierten Regelssammlung von FontsManager
    IFontFallBackRulesCollection rulesList = pres.FontsManager.FontFallBackRulesCollection;

    //Hinzufügen einer neuen Regel zur Sammlung
    rulesList.Add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
}
```

### Siehe auch

* interface [IFontFallBackRule](../../ifontfallbackrule)
* interface [IFontFallBackRulesCollection](../../ifontfallbackrulescollection)
* namespace [Aspose.Slides](../../ifontfallbackrulescollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
