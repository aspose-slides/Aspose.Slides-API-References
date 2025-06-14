---
title: IMathParagraph
second_title: Aspose.Slides für .NET API-Referenz
description: Mathematischer Absatz, der ein Container für mathematische Blöcke IMathBlock ist
type: docs
weight: 8140
url: /de/aspose.slides.mathtext/imathparagraph/
---

## IMathParagraph-Schnittstelle

Mathematischer Absatz, der ein Container für mathematische Blöcke (IMathBlock) ist

```csharp
public interface IMathParagraph : IMathBlockCollection
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIMathBlockCollection](../../aspose.slides.mathtext/imathparagraph/asimathblockcollection) { get; } | Ermöglicht den Zugriff auf die basale IMathBlockCollection-Schnittstelle [`IMathBlockCollection`](../imathblockcollection) |
| [Justification](../../aspose.slides.mathtext/imathparagraph/justification) { get; set; } | Absatzjustierung Standardwert: ZentriertAlsGruppe |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ToLatex](../../aspose.slides.mathtext/imathparagraph/tolatex)() | Erhält mathematische Gleichung im LaTeX-Format |
| [WriteAsMathMl](../../aspose.slides.mathtext/imathparagraph/writeasmathml)(Stream) | Speichert den Inhalt dieses [`IMathParagraph`](../imathparagraph) als MathML |

### Beispiele

Beispiel:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
mathParagraph.Justification = MathJustification.LeftJustified;
```

### Siehe auch

* Schnittstelle [IMathBlockCollection](../imathblockcollection)
* Namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->