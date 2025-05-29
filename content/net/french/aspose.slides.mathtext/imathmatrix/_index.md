---
title: IMathMatrix
second_title: Aspose.Slides pour la référence de l'API .NET
description: Spécifie l'objet Matrix constitué d'éléments enfants disposés en une ou plusieurs lignes et colonnes. Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. Pour placer la matrice entre des parenthèses, vous devez utiliser l'objet délimiteur IMathDelimiter. Des arguments nuls peuvent être utilisés pour créer des espaces dans les matrices.
type: docs
weight: 8090
url: /fr/aspose.slides.mathtext/imathmatrix/
---

## Interface IMathMatrix

Spécifie l'objet Matrix, constitué d'éléments enfants disposés en une ou plusieurs lignes et colonnes. Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. Pour placer la matrice entre des parenthèses, vous devez utiliser l'objet délimiteur (IMathDelimiter). Des arguments nuls peuvent être utilisés pour créer des espaces dans les matrices.

```csharp
public interface IMathMatrix : IMathElement
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Permet d'obtenir l'interface de base IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Spécifie la justification verticale par rapport au texte environnant. Les valeurs possibles sont haut, bas et centre. Par défaut : Centre |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Nombre de colonnes dans la matrice |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | La valeur de l'espacement horizontal entre les colonnes d'une matrice ; Si le ColumnGapRule est défini sur 3 ("Exactement"), alors l'unité est interprétée comme des twips (1/20ème d'un point) Si le ColumnGapRule est défini sur 4 ("Multiple"), alors l'unité est interprétée comme le nombre d'incréments de 0,5 em. Dans d'autres cas, ignoré. Par défaut : 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Le type d'espacement horizontal entre les colonnes d'une matrice ; Les unités d'espacement horizontal peuvent être des ems ou des points (stockés sous forme de twips). Par défaut : SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Masquer les espaces réservés pour les éléments de matrice vides. Par défaut : false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Éléments de matrice |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Largeur minimale de colonne en twips (1/20ème d'un point) L'espacement de la marge (également appelé “Column Gap” ou “Gap Width”) est ajouté à la MinColumnWidth pour déterminer l'espacement total des colonnes de la matrice (distance entre les bords identiques de différentes colonnes). Par défaut : 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Nombre de lignes dans la matrice |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | La valeur de l'espacement vertical entre les lignes d'une matrice ; Si le RowGapRule est défini sur 3 ("Exactement"), alors l'unité est interprétée comme des twips (1/20ème d'un point) Si le RowGapRule est défini sur 4 ("Multiple"), alors l'unité est interprétée comme des demi-lignes. Par défaut : 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Le type d'espacement vertical entre les lignes d'une matrice ; Les unités d'espacement vertical peuvent être des lignes ou des points (stockés sous forme de twips). Par défaut : SingleSpacingGap (0) |

## Méthodes

| Nom | Description |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Supprime la colonne spécifiée |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Supprime la ligne spécifiée |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Obtient l'alignement horizontal de la colonne spécifiée |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Insère une nouvelle colonne après celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont nuls. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Insère une nouvelle colonne avant celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont nuls. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Insère une nouvelle ligne après celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont nuls. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Insère une nouvelle ligne avant celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont nuls. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Définit l'alignement horizontal de la colonne spécifiée |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Définit l'alignement horizontal des colonnes spécifiées |

### Exemples

Exemple :

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Voir aussi

* interface [IMathElement](../imathelement)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->