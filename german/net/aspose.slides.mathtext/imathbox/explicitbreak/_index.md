---
title: ExplicitBreak
second_title: Aspose.Slides für .NET-API-Referenz
description: Expliziter Umbruch gibt an ob es am Anfang des BoxObjekts einen Zeilenumbruch gibt so dass die Zeile am Anfang des BoxObjekts umbricht. Gibt die Nummer des Operators in der vorherigen Zeile des mathematischen Texts an der verwendet werden soll als Ausrichtungspunkt für die aktuelle Zeile des mathematischen Textes mögliche Werte 1..255 Default 0 kein expliziter Umbruch
type: docs
weight: 50
url: /de/net/aspose.slides.mathtext/imathbox/explicitbreak/
---
## IMathBox.ExplicitBreak property

Expliziter Umbruch gibt an, ob es am Anfang des Box-Objekts einen Zeilenumbruch gibt, so, dass die Zeile am Anfang des Box-Objekts umbricht. Gibt die Nummer des Operators in der vorherigen Zeile des mathematischen Texts an, der verwendet werden soll als Ausrichtungspunkt für die aktuelle Zeile des mathematischen Textes mögliche Werte: 1..255 Default: 0 (kein expliziter Umbruch)

```csharp
public byte ExplicitBreak { get; set; }
```

### Beispiele

Beispiel:

```csharp
[C#]
IMathBox box = new MathematicalText("==").ToBox();
box.ExplicitBreak = 1;
```

### Siehe auch

* interface [IMathBox](../../imathbox)
* namensraum [Aspose.Slides.MathText](../../imathbox)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->