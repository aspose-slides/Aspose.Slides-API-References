---
title: RemoveAt
second_title: Aspose.Slides für .NET-API-Referenz
description: Entfernt das Element am angegebenen Index der Sammlung.
type: docs
weight: 170
url: /de/net/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock.RemoveAt method

Entfernt das Element am angegebenen Index der Sammlung.

```csharp
public void RemoveAt(int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Der nullbasierte Index des zu entfernenden Elements. |

### Beispiele

Beispiel:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
mathBlock.Add(plusElement);
mathBlock.Insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
mathBlock.RemoveAt(2);
```

### Siehe auch

* class [MathBlock](../../mathblock)
* namensraum [Aspose.Slides.MathText](../../mathblock)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->