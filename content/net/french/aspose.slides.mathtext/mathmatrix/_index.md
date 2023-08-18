---
title: MathMatrix
second_title: Référence de l'API Aspose.Slides pour .NET
description: Spécifie lobjet Matrix composé déléments enfants disposés sur une ou plusieurs lignes et colonnes. Il est important de noter que les matrices nont pas de délimiteurs intégrés. Pour placer la matrice entre parenthèses vous devez utiliser lobjet délimiteur IMathDelimiter. Des arguments nuls peuvent être utilisés pour créer des espaces dans les matrices.
type: docs
weight: 8160
url: /fr/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix class

Spécifie l'objet Matrix, composé d'éléments enfants disposés sur une ou plusieurs lignes et colonnes. Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. Pour placer la matrice entre parenthèses, vous devez utiliser l'objet délimiteur (IMathDelimiter). Des arguments nuls peuvent être utilisés pour créer des espaces dans les matrices.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Initialise une nouvelle instance de la classe MathMatrix. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Spécifie la justification verticale par rapport au texte environnant. Les valeurs possibles sont top, bottom et center. Par défaut : Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Nombre de colonnes dans la matrice |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | La valeur de l'espacement horizontal entre les colonnes d'une matrice ; Si ColumnGapRule est défini sur 3 ("Exactly"), l'unité est interprétée comme des twips (1/20e de point) Si ColumnGapRule est défini sur 4 ( "Multiple"), l'unité est interprétée comme un nombre d'incréments de 0,5 em. Dans les autres cas, ignoré. Par défaut : 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Le type d'espacement horizontal entre les colonnes d'une matrice ; Les unités d'espacement horizontal peuvent être des ems ou des points (stockés sous forme de twips). Par défaut : SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Masquer les espaces réservés pour les éléments de matrice vides Par défaut : false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Elément de matrice |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Largeur de colonne minimale en twips (1/20e de point) L'espacement de l'espacement (également appelé « Espacement de la colonne » ou « Largeur de l'espacement ») est ajouté à la MinColumnWidth pour déterminer l'espacement total des colonnes de la matrice (distance entre les mêmes arêtes de colonnes différentes). Par défaut : 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Nombre de lignes dans la matrice |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | La valeur de l'espacement vertical entre les lignes d'une matrice ; Si le RowGapRule est défini sur 3 ("Exactement"), l'unité est interprétée comme des twips (1/20e de point) Si le RowGapRule est défini sur 4 ( "Multiple"), alors l'unité est interprétée comme des demi-lignes. Par défaut : 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Le type d'espacement vertical entre les lignes d'une matrice ; Les unités d'espacement vertical peuvent être des lignes ou des points (stockés sous forme de twips). Par défaut : SingleSpacingGap (0) |

## Méthodes

| Nom | La description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Définit une marque d'accent (un caractère en haut de cet élément) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Supprime la colonne spécifiée |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Supprime la ligne spécifiée |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Encadre un élément mathématique entre parenthèses |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Encadre un élément mathématique dans des caractères spécifiés tels que des parenthèses ou d'autres caractères comme framing |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Prend une fonction d'un argument en utilisant cette instance comme fonction name |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Prend une fonction d'un argument en utilisant cette instance comme fonction name |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Obtenir les éléments enfants |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Obtenir l'alignement horizontal de la colonne spécifiée |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Place cet élément dans un groupe à l'aide d'une accolade inférieure |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Place cet élément dans un groupe à l'aide d'un caractère de regroupement tel qu'une accolade inférieure ou un autre |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Insérer une nouvelle colonne après celle spécifiée Initialement, tous les éléments de la nouvelle colonne sont nuls. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Insérer une nouvelle colonne avant celle spécifiée Initialement, tous les éléments de la nouvelle colonne sont nuls. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Insérer une nouvelle ligne après celle spécifiée Initialement, tous les éléments de la nouvelle ligne sont nuls. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Insérer une nouvelle ligne avant celle spécifiée Initialement, tous les éléments de la nouvelle ligne sont nuls. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Prend l'intégrale sans limites |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Prend l'intégrale |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Joint un élément mathématique et forme un bloc mathématique |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Joint un texte mathématique et forme un bloc mathématique |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crée un opérateur N-aire |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Crée un opérateur N-aire |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Définit une barre en haut de cet élément |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Définir l'alignement horizontal de la colonne spécifiée |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Définir l'alignement horizontal des colonnes spécifiées |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Prend la limite inférieure |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Prend la limite inférieure |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crée un indice |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crée un indice |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crée un indice et un exposant à gauche |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crée un indice et un exposant à gauche |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crée un indice et un exposant à droite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crée un indice et un exposant à droite |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crée un exposant |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crée un exposant |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Prend la limite supérieure |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Prend la limite supérieure |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Place cet élément dans une border-box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Place cet élément dans une border-box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Place cet élément dans une boîte non visuelle (groupement logique) qui est utilisée pour regrouper les composants d'une équation ou d'une autre instance de texte mathématique. Un objet encadré peut (par exemple) servir d'émulateur d'opérateur avec ou sans alignement point, servir de point de rupture de ligne, ou être regroupés de manière à ne pas autoriser les sauts de ligne à l'intérieur. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Place dans un tableau vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Définit une barre au bas de cet élément |

### Exemples

Exemple :

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Voir également

* class [MathElementBase](../mathelementbase)
* interface [IMathMatrix](../imathmatrix)
* espace de noms [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
