---
title: IndexOf
second_title: Référence de l'API Aspose.Slides pour .NET
description: Détermine lindex dun IMathBlock spécifique dans la collection.
type: docs
weight: 80
url: /fr/aspose.slides.mathtext/mathparagraph/indexof/
---
## MathParagraph.IndexOf method

Détermine l'index d'un IMathBlock spécifique dans la collection.

```csharp
public int IndexOf(IMathBlock mathBlock)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| mathBlock | IMathBlock | L'élément à localiser dans la collection. |

### Return_Value

L'indice de*mathBlock* s'il se trouve dans la collection ; sinon, -1.

### Exemples

Exemple :

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
IMathBlock block = new MathBlock(new MathematicalText("y"));
mathParagraph.Add(block);
int index = mathParagraph.IndexOf(block);
```

### Voir également

* interface [IMathBlock](../../imathblock)
* class [MathParagraph](../../mathparagraph)
* espace de noms [Aspose.Slides.MathText](../../mathparagraph)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
