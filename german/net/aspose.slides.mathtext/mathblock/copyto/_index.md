---
title: CopyTo
second_title: Aspose.Slides für .NET-API-Referenz
description: In angegebenes Array kopieren.
type: docs
weight: 80
url: /de/net/aspose.slides.mathtext/mathblock/copyto/
---
## MathBlock.CopyTo method

In angegebenes Array kopieren.

```csharp
public void CopyTo(IMathElement[] array, int arrayIndex)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | IMathElement[] | Array, in das kopiert werden soll. |
| arrayIndex | Int32 | Index, um mit dem Kopieren zu beginnen. |

### Beispiele

Beispiel:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
mathBlock.Add(plusElement);
mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
mathBlock.CopyTo(destinationArray, 0);
```

### Siehe auch

* interface [IMathElement](../../imathelement)
* class [MathBlock](../../mathblock)
* namensraum [Aspose.Slides.MathText](../../mathblock)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->