---
title: Insert
second_title: Aspose.Slides für .NET-API-Referenz
description: Fügt ein MathElement am angegebenen Index in die Sammlung ein.
type: docs
weight: 130
url: /de/net/aspose.slides.mathtext/mathblock/insert/
---
## MathBlock.Insert method

Fügt ein MathElement am angegebenen Index in die Sammlung ein.

```csharp
public void Insert(int index, IMathElement item)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Der nullbasierte Index, an dem MathElement eingefügt werden soll. |
| item | IMathElement | Das einzufügende MathElement. |

### Beispiele

Beispiel:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
mathBlock.Add(plusElement);
mathBlock.Insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
```

### Siehe auch

* interface [IMathElement](../../imathelement)
* class [MathBlock](../../mathblock)
* namensraum [Aspose.Slides.MathText](../../mathblock)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->