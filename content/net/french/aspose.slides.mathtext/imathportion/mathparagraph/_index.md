---
title: MathParagraph
second_title: Référence de l'API Aspose.Slides pour .NET
description: Paragraphe mathématique
type: docs
weight: 10
url: /fr/aspose.slides.mathtext/imathportion/mathparagraph/
---
## IMathPortion.MathParagraph property

Paragraphe mathématique

```csharp
public IMathParagraph MathParagraph { get; }
```

### Exemples

Exemple :

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAutoShape shape = pres.Slides[0].Shapes.AddMathShape(0, 0, 300, 50);
    IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
    mathParagraph.Add(new MathBlock(new MathematicalText("x+y")));
}
```

### Voir également

* interface [IMathParagraph](../../imathparagraph)
* interface [IMathPortion](../../imathportion)
* espace de noms [Aspose.Slides.MathText](../../imathportion)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
