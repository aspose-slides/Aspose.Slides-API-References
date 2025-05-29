---
title: IMathParagraph
second_title: Referencia de API de Aspose.Slides para .NET
description: Párrafo matemático que es un contenedor para bloques matemáticos IMathBlock
type: docs
weight: 8140
url: /es/aspose.slides.mathtext/imathparagraph/
---

## Interfaz IMathParagraph

Párrafo matemático que es un contenedor para bloques matemáticos (IMathBlock)

```csharp
public interface IMathParagraph : IMathBlockCollection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIMathBlockCollection](../../aspose.slides.mathtext/imathparagraph/asimathblockcollection) { get; } | Permite obtener la interfaz base IMathBlockCollection [`IMathBlockCollection`](../imathblockcollection) |
| [Justification](../../aspose.slides.mathtext/imathparagraph/justification) { get; set; } | Justificación del párrafo Valor predeterminado: CenteredAsGroup |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ToLatex](../../aspose.slides.mathtext/imathparagraph/tolatex)() | Obtiene la ecuación matemática en formato LaTeX |
| [WriteAsMathMl](../../aspose.slides.mathtext/imathparagraph/writeasmathml)(Stream) | Guarda el contenido de este [`IMathParagraph`](../imathparagraph) como MathML |

### Ejemplos

Ejemplo:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
mathParagraph.Justification = MathJustification.LeftJustified;
```

### Véase También

* interfaz [IMathBlockCollection](../imathblockcollection)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->