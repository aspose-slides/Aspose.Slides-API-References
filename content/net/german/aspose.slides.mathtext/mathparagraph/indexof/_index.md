---
title: IndexOf
second_title: Aspose.Slides für .NET API Referenz
description: Bestimmt den Index eines spezifischen IMathBlock in der Sammlung.
type: docs
weight: 80
url: /de/aspose.slides.mathtext/mathparagraph/indexof/
---

## MathParagraph.IndexOf Methode

Bestimmt den Index eines spezifischen IMathBlock in der Sammlung.

```csharp
public int IndexOf(IMathBlock mathBlock)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathBlock | IMathBlock | Das Element, das in der Sammlung lokalisiert werden soll. |

### Rückgabewert

Der Index von *mathBlock*, falls in der Sammlung gefunden; andernfalls -1.

### Beispiele

Beispiel:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
IMathBlock block = new MathBlock(new MathematicalText("y"));
mathParagraph.Add(block);
int index = mathParagraph.IndexOf(block);
```

### Siehe auch

* Schnittstelle [IMathBlock](../../imathblock)
* Klasse [MathParagraph](../../mathparagraph)
* Namensraum [Aspose.Slides.MathText](../../mathparagraph)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->