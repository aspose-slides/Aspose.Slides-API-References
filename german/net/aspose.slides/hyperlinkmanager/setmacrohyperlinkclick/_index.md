---
title: SetMacroHyperlinkClick
second_title: Aspose.Slides für .NET-API-Referenz
description: MakroHyperlink auf einen Klick setzen.
type: docs
weight: 70
url: /de/net/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager.SetMacroHyperlinkClick method

Makro-Hyperlink auf einen Klick setzen.

```csharp
public IHyperlink SetMacroHyperlinkClick(string macroName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| macroName | String | Name des Makros |

### Rückgabewert

Hyperlink-Objekt[`IHyperlink`](../../ihyperlink)

### Beispiele

```csharp
[C#]
using (Presentation presentation = new Presentation())
{
    IAutoShape shape = presentation.Slides[0].Shapes.AddAutoShape(ShapeType.BlankButton, 20, 20, 80, 30);
    shape.HyperlinkManager.SetMacroHyperlinkClick("MacroName");
}
```

### Siehe auch

* interface [IHyperlink](../../ihyperlink)
* class [HyperlinkManager](../../hyperlinkmanager)
* namensraum [Aspose.Slides](../../hyperlinkmanager)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->