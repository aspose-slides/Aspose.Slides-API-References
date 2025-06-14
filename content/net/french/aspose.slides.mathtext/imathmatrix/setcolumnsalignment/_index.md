---
title: SetColumnsAlignment
second_title: Aspose.Slides pour la référence de l'API .NET
description: Définir l'alignement horizontal des colonnes spécifiées
type: docs
weight: 200
url: /fr/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---

## IMathMatrix.SetColumnsAlignment method

Définir l'alignement horizontal des colonnes spécifiées

```csharp
public void SetColumnsAlignment(int columnIndex, uint columnsCount, MathHorizontalAlignment val)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | Int32 | Index basé sur zéro de la première colonne à aligner |
| columnsCount | UInt32 | Le nombre de colonnes pour spécifier l'alignement |
| val | MathHorizontalAlignment | Nouvelle valeur de l'alignement horizontal de la colonne spécifiée |

### Exemples

Exemple :

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.SetColumnAlignment(0, 3, MathHorizontalAlignment.Left);
```

### Voir aussi

* enum [MathHorizontalAlignment](../../mathhorizontalalignment)
* interface [IMathMatrix](../../imathmatrix)
* namespace [Aspose.Slides.MathText](../../imathmatrix)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->