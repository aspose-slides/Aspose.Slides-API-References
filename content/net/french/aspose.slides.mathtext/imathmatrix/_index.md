---
title: IMathMatrix
second_title: Aspose.Sildes pour .NET – Référence API
description: Spécifie l'objet Matrix composé d'éléments enfants disposés sur une ou plusieurs lignes et colonnes. Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. Pour placer la matrice entre crochets, vous devez utiliser l'objet délimiteur IMathDelimiter. Les arguments null peuvent être utilisés pour créer des espaces dans les matrices.
type: docs
weight: 8340
url: /fr/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix interface

Spécifie l'objet Matrix, composé d'éléments enfants disposés sur une ou plusieurs lignes et colonnes. Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. Pour placer la matrice entre crochets, vous devez utiliser l'objet délimiteur (IMathDelimiter). Des arguments null peuvent être utilisés pour créer des espaces dans les matrices.

```csharp
public interface IMathMatrix : IMathElement
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Permet d'obtenir l'interface de base IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Spécifie la justification verticale par rapport au texte environnant. Les valeurs possibles sont top, bottom et center. Valeur par défaut : Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Nombre de colonnes dans la matrice |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Valeur de l'espacement horizontal entre les colonnes d'une matrice ; si ColumnGapRule est défini à 3 ("Exactly"), l'unité est interprétée en twips (1/20e de point). Si ColumnGapRule est défini à 4 ("Multiple"), l'unité est interprétée comme un nombre d'incréments de 0,5 em. Dans les autres cas, ignoré. Valeur par défaut : 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Type de l'espacement horizontal entre les colonnes d'une matrice ; les unités d'espacement horizontal peuvent être des ems ou des points (stockés en twips). Valeur par défaut : SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Masque les espaces réservés pour les éléments vides de la matrice. Valeur par défaut : false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Éléments de la matrice |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Largeur minimale de la colonne en twips (1/20e de point). L'espacement de l'écart (également appelé « Column Gap » ou « Gap Width ») est ajouté à MinColumnWidth pour déterminer l'espacement total des colonnes de la matrice (distance entre les mêmes bords de colonnes différentes). Valeur par défaut : 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Nombre de lignes dans la matrice |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Valeur de l'espacement vertical entre les lignes d'une matrice ; si RowGapRule est défini à 3 ("Exactly"), l'unité est interprétée en twips (1/20e de point). Si RowGapRule est défini à 4 ("Multiple"), l'unité est interprétée comme des demi-lignes. Valeur par défaut : 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Type de l'espacement vertical entre les lignes d'une matrice ; les unités d'espacement vertical peuvent être des lignes ou des points (stockés en twips). Valeur par défaut : SingleSpacingGap (0) |

## Méthodes

| Nom | Description |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Supprime la colonne spécifiée |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Supprime la ligne spécifiée |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Obtient l'alignement horizontal de la colonne spécifiée |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Insère une nouvelle colonne après celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Insère une nouvelle colonne avant celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Insère une nouvelle ligne après celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Insère une nouvelle ligne avant celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Définit l'alignement horizontal de la colonne spécifiée |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Définit l'alignement horizontal des colonnes spécifiées |

### Exemples

Exemple :

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Voir aussi

* interface [IMathElement](../imathelement)
* espace de noms [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->