---
title: Remove
second_title: Aspose.Sildes für .NET API Referenz
description: Entfernt die erste Vorkommen einer bestimmten FallBack-Regel aus der Sammlung.
type: docs
weight: 30
url: /de/aspose.slides/ifontfallbackrulescollection/remove/
---

## IFontFallBackRulesCollection.Remove Methode

Entfernt die erste Vorkommen einer bestimmten FallBack-Regel aus der Sammlung.

```csharp
public void Remove(IFontFallBackRule targetRule)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetRule | IFontFallBackRule | Die Regel, die aus der Sammlung entfernt werden soll. |

### Beispiele

```csharp
[C#]
using (Presentation pres = new Presentation ())
{
    //Erhalten einer leeren oder vorinitialisierten Regel-Sammlung von FontsManager
    IFontFallBackRulesCollection rulesList = pres.FontsManager.FontFallBackRulesCollection;

    //Hinzufügen mehrerer Regeln zur Sammlung
    rulesList.Add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
    rulesList.Add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));

    //Abrufen des Objekts der ersten Regel in der Sammlung
    IFontFallBackRule firstRule = rulesList[0];
    //Entfernen 
    rulesList.Remove (firstRule);
}
```

### Siehe Auch

* interface [IFontFallBackRule](../../ifontfallbackrule)
* interface [IFontFallBackRulesCollection](../../ifontfallbackrulescollection)
* namespace [Aspose.Slides](../../ifontfallbackrulescollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->