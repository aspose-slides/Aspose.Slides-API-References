---
title: IMathMatrix
second_title: Référence de l'API Aspose.Slides pour .NET
description: Spécifie lobjet Matrix composé déléments enfants disposés sur une ou plusieurs lignes et colonnes. Il est important de noter que les matrices nont pas de délimiteurs intégrés. Pour placer la matrice entre parenthèses vous devez utiliser lobjet délimiteur IMathDelimiter. Des arguments nuls peuvent être utilisés pour créer des espaces dans les matrices.
type: docs
weight: 7660
url: /fr/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix interface

Spécifie l'objet Matrix, composé d'éléments enfants disposés sur une ou plusieurs lignes et colonnes. Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. Pour placer la matrice entre parenthèses, vous devez utiliser l'objet délimiteur (IMathDelimiter). Des arguments nuls peuvent être utilisés pour créer des espaces dans les matrices.

```csharp
public interface IMathMatrix : IMathElement
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Permet d'obtenir l'interface IMathElement de base [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Spécifie la justification verticale par rapport au texte environnant. Les valeurs possibles sont top, bottom et center. Par défaut : Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Nombre de colonnes dans la matrice |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | La valeur de l'espacement horizontal entre les colonnes d'une matrice ; Si ColumnGapRule est défini sur 3 ("Exactly"), l'unité est interprétée comme des twips (1/20e de point) Si ColumnGapRule est défini sur 4 ( "Multiple"), l'unité est interprétée comme un nombre d'incréments de 0,5 em. Dans les autres cas, ignoré. Par défaut : 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Le type d'espacement horizontal entre les colonnes d'une matrice ; Les unités d'espacement horizontal peuvent être des ems ou des points (stockés sous forme de twips). Par défaut : SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Masquer les espaces réservés pour les éléments de matrice vides Par défaut : false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Eléments de matrice |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Largeur de colonne minimale en twips (1/20e de point) L'espacement de l'espacement (également appelé « Espacement de la colonne » ou « Largeur de l'espacement ») est ajouté à la MinColumnWidth pour déterminer l'espacement total des colonnes de la matrice (distance entre les mêmes arêtes de colonnes différentes). Par défaut : 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Nombre de lignes dans la matrice |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | La valeur de l'espacement vertical entre les lignes d'une matrice ; Si le RowGapRule est défini sur 3 ("Exactement"), l'unité est interprétée comme des twips (1/20e de point) Si le RowGapRule est défini sur 4 ( "Multiple"), alors l'unité est interprétée comme des demi-lignes. Par défaut : 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Le type d'espacement vertical entre les lignes d'une matrice ; Les unités d'espacement vertical peuvent être des lignes ou des points (stockés sous forme de twips). Par défaut : SingleSpacingGap (0) |

## Méthodes

| Nom | La description |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Supprime la colonne spécifiée |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Supprime la ligne spécifiée |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Obtenir l'alignement horizontal de la colonne spécifiée |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Insérer une nouvelle colonne après celle spécifiée Initialement, tous les éléments de la nouvelle colonne sont nuls. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Insérer une nouvelle colonne avant celle spécifiée Initialement, tous les éléments de la nouvelle colonne sont nuls. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Insérer une nouvelle ligne après celle spécifiée Initialement, tous les éléments de la nouvelle ligne sont nuls. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Insérer une nouvelle ligne avant celle spécifiée Initialement, tous les éléments de la nouvelle ligne sont nuls. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Définir l'alignement horizontal de la colonne spécifiée |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Définir l'alignement horizontal des colonnes spécifiées |

### Exemples

Exemple :

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Voir également

* interface [IMathElement](../imathelement)
* espace de noms [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
