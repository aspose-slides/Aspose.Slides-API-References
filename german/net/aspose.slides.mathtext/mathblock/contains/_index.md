---
title: Contains
second_title: Aspose.Slides für .NET-API-Referenz
description: Bestimmt ob die Sammlung einen bestimmten Wert enthält.
type: docs
weight: 70
url: /de/net/aspose.slides.mathtext/mathblock/contains/
---
## MathBlock.Contains method

Bestimmt, ob die Sammlung einen bestimmten Wert enthält.

```csharp
public bool Contains(IMathElement item)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | IMathElement | Das Objekt, das in der Auflistung gesucht werden soll. |

### Rückgabewert

wahr, wenn*item* befindet sich in der Sammlung; andernfalls falsch.

### Beispiele

Beispiel:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
mathBlock.Add(plusElement);
mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
bool contains = mathBlock.Contains(plusElement);
```

### Siehe auch

* interface [IMathElement](../../imathelement)
* class [MathBlock](../../mathblock)
* namensraum [Aspose.Slides.MathText](../../mathblock)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->