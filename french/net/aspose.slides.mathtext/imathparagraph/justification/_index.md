---
title: Justification
second_title: Référence de l'API Aspose.Slides pour .NET
description: Justification du paragraphe Valeur par défaut  CenteredAsGroup
type: docs
weight: 20
url: /fr/net/aspose.slides.mathtext/imathparagraph/justification/
---
## IMathParagraph.Justification property

Justification du paragraphe Valeur par défaut : CenteredAsGroup

```csharp
public MathJustification Justification { get; set; }
```

### Exemples

Exemple :

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
mathParagraph.Justification = MathJustification.LeftJustified;
```

### Voir également

* enum [MathJustification](../../mathjustification)
* interface [IMathParagraph](../../imathparagraph)
* espace de noms [Aspose.Slides.MathText](../../imathparagraph)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->