---
title: Remove
second_title: Aspose.Slides für .NET-API-Referenz
description: Entfernt das erste Vorkommen einer bestimmten FallBackSchriftart aus der Liste.
type: docs
weight: 80
url: /de/net/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule.Remove method

Entfernt das erste Vorkommen einer bestimmten FallBack-Schriftart aus der Liste.

```csharp
public void Remove(string fontName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Der Name der Schriftart, die aus der Liste entfernt werden soll. |

### Beispiele

```csharp
[C#]
// Erstellen Sie eine Regel, die eine Liste von Schriftarten enthält.
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

//Entfernen von Tahoma von der Liste
newRule.Remove ("Tahoma");
```

### Siehe auch

* interface [IFontFallBackRule](../../ifontfallbackrule)
* namensraum [Aspose.Slides](../../ifontfallbackrule)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->