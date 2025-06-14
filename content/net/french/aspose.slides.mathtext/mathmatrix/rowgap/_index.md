---
title: RowGap
second_title: Référence de l'API Aspose.Slides pour .NET
description: La valeur de l'espacement vertical entre les lignes d'une matrice. Si la RowGapRule est réglée sur 3 "Exactement", alors l'unité est interprétée comme des twips 1/20e d'un point. Si la RowGapRule est réglée sur 4 "Multiple", alors l'unité est interprétée comme des demi-lignes. Par défaut  0
type: docs
weight: 100
url: /fr/aspose.slides.mathtext/mathmatrix/rowgap/
---

## MathMatrix.RowGap property

La valeur de l'espacement vertical entre les lignes d'une matrice ; Si la RowGapRule est réglée sur 3 ("Exactement"), alors l'unité est interprétée comme des twips (1/20e d'un point). Si la RowGapRule est réglée sur 4 ("Multiple"), alors l'unité est interprétée comme des demi-lignes. Par défaut : 0

```csharp
public uint RowGap { get; set; }
```

### Exemples

Exemple :

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.RowGapRule = MathSpacingRules.Exactly;
matrix.RowGap = 20;
```

### Voir aussi

* classe [MathMatrix](../../mathmatrix)
* espace de noms [Aspose.Slides.MathText](../../mathmatrix)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->