---
title: Remove
second_title: Aspose.Slides für .NET API Referenz
description: Entfernt das erste Vorkommen einer bestimmten FallBack-Schriftart aus der Liste.
type: docs
weight: 80
url: /de/aspose.slides/ifontfallbackrule/remove/
---

## IFontFallBackRule.Remove Methode

Entfernt das erste Vorkommen einer bestimmten FallBack-Schriftart aus der Liste.

```csharp
public void Remove(string fontName)
```

| Parameter  | Typ    | Beschreibung                                                |
|------------|--------|-----------------------------------------------------------|
| fontName   | String | Der Name der Schriftart, der aus der Liste entfernt werden soll. |

### Beispiele

```csharp
[C#]
// Erstellen Sie eine Regel, die eine Liste von Schriftarten enthält.
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

// Entfernen von Tahoma aus der Liste
newRule.Remove("Tahoma");
```

### Siehe Auch

* Schnittstelle [IFontFallBackRule](../../ifontfallbackrule)
* Namespace [Aspose.Slides](../../ifontfallbackrule)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->