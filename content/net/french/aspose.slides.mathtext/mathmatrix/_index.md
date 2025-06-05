---
title: MathMatrix
second_title: Référence de l'API Aspose.Slides pour .NET
description: Spécifie l'objet Matrix composé d'éléments enfants disposés en une ou plusieurs lignes et colonnes. Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. Pour placer la matrice dans les parenthèses, vous devez utiliser l'objet de délimiteur IMathDelimiter. Des arguments nuls peuvent être utilisés pour créer des espaces dans les matrices.
type: docs
weight: 8590
url: /fr/aspose.slides.mathtext/mathmatrix/
---

## MathMatrix class

Spécifie l'objet Matrix, composé d'éléments enfants disposés en une ou plusieurs lignes et colonnes. Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. Pour placer la matrice dans les parenthèses, vous devez utiliser l'objet de délimiteur (IMathDelimiter). Des arguments nuls peuvent être utilisés pour créer des espaces dans les matrices.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Initialise une nouvelle instance de la classe MathMatrix. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Spécifie la justification verticale par rapport au texte environnant. Les valeurs possibles sont haut, bas et centre. Par défaut : Centre |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Nombre de colonnes dans la matrice |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | La valeur de l'espacement horizontal entre les colonnes d'une matrice ; Si le ColumnGapRule est défini sur 3 ("Exact"), alors l'unité est interprétée comme des twips (1/20ème d'un point) Si le ColumnGapRule est défini sur 4 ("Multiple"), alors l'unité est interprétée comme le nombre d'incréments de 0.5 em. Dans d'autres cas, ignoré. Par défaut : 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Le type d'espacement horizontal entre les colonnes d'une matrice ; Les unités d'espacement horizontal peuvent être des ems ou des points (stockés sous forme de twips). Par défaut : SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Masque les espaces réservés pour les éléments de matrice vides. Par défaut : faux |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Élément de la matrice |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Largeur minimale de colonne en twips (1/20ème d'un point). L'espacement des écarts (également appelé "Espacement de colonne" ou "Largeur d'écart") est ajouté à la MinColumnWidth pour déterminer le total de Matrix Column Spacing (distance entre les mêmes bords de différentes colonnes). Par défaut : 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Nombre de lignes dans la matrice |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | La valeur de l'espacement vertical entre les lignes d'une matrice ; Si le RowGapRule est défini sur 3 ("Exact"), alors l'unité est interprétée comme des twips (1/20ème d'un point) Si le RowGapRule est défini sur 4 ("Multiple"), alors l'unité est interprétée comme des demi-lignes. Par défaut : 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Le type d'espacement vertical entre les lignes d'une matrice ; Les unités d'espacement vertical peuvent être des lignes ou des points (stockés sous forme de twips). Par défaut : SingleSpacingGap (0) |

## Méthodes

| Nom | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Définit un accent (un caractère au-dessus de cet élément) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Prend une fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Prend une fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Prend une fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Prend une fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Prend une fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Supprime la colonne spécifiée |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Supprime la ligne spécifiée |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crée une fraction avec ce numérateur et ce dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crée une fraction avec ce numérateur et ce dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et ce dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et ce dénominateur spécifié |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Enveloppe un élément mathématique dans des parenthèses |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Enveloppe un élément mathématique dans des caractères spécifiés tels que des parenthèses ou d'autres caractères en tant qu'encadrement |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Obtenir les éléments enfants |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Obtenir l'alignement horizontal de la colonne spécifiée |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Place cet élément dans un groupe en utilisant une accolade courbe inférieure |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Place cet élément dans un groupe en utilisant un caractère de regroupement tel qu'une accolade courbe inférieure ou autre |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Insère une nouvelle colonne après celle spécifiée. Au départ, tous les éléments de la nouvelle colonne sont nuls. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Insère une nouvelle colonne avant celle spécifiée. Au départ, tous les éléments de la nouvelle colonne sont nuls. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Insère une nouvelle ligne après celle spécifiée. Au départ, tous les éléments de la nouvelle ligne sont nuls. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Insère une nouvelle ligne avant celle spécifiée. Au départ, tous les éléments de la nouvelle ligne sont nuls. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Prend l'intégrale sans limites |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Prend l'intégrale |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Joint un élément mathématique et forme un bloc mathématique |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Joint un texte mathématique et forme un bloc mathématique |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crée un opérateur N-aire |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Crée un opérateur N-aire |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Définit une barre sur le dessus de cet élément |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Définit l'alignement horizontal de la colonne spécifiée |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Définit l'alignement horizontal des colonnes spécifiées |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Prend la limite inférieure |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Prend la limite inférieure |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crée une note de bas de page |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crée une note de bas de page |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crée une note de bas de page et un exposant à gauche |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crée une note de bas de page et un exposant à gauche |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crée une note de bas de page et un exposant à droite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crée une note de bas de page et un exposant à droite |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crée un exposant |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crée un exposant |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Prend la limite supérieure |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Prend la limite supérieure |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Place cet élément dans une bordure |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Place cet élément dans une bordure |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Place cet élément dans une boîte non visuelle (regroupement logique) qui est utilisée pour regrouper les composants d'une équation ou d'autres instances de texte mathématique. Un objet encapsulé peut (par exemple) servir d'émulateur d'opérateur avec ou sans point d'alignement, servir de point de retour à la ligne, ou être regroupé de manière à ne pas permettre les retours à la ligne à l'intérieur. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Met dans un tableau vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Définit une barre au bas de cet élément |

### Exemples

Exemple :

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Voir aussi

* class [MathElementBase](../mathelementbase)
* interface [IMathMatrix](../imathmatrix)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->