---
title: MathBlock
second_title: Référence de l'API Aspose.Slides pour .NET
description: Spécifie une instance de texte mathématique contenue dans un MathParagraph et qui commence sur sa propre ligne. Toutes les zones mathématiques, y compris les équations, expressions, tableaux d'équations ou expressions, et formules, sont représentées par un bloc mathématique.
type: docs
weight: 8330
url: /fr/aspose.slides.mathtext/mathblock/
---

## MathBlock class

Spécifie une instance de texte mathématique contenue dans un MathParagraph et qui commence sur sa propre ligne. Toutes les zones mathématiques, y compris les équations, expressions, tableaux d'équations ou expressions, et formules, sont représentées par un bloc mathématique.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Initialise une nouvelle instance de la classe MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Crée un nouveau bloc mathématique et y met les éléments spécifiés. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Crée un nouveau bloc mathématique et y met l'élément spécifié. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Obtient le nombre d'éléments mathématiques enfants réellement contenus dans la collection. Lecture seule Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Retourne false car la collection d'éléments enfants peut être modifiée. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Obtient ou définit IMathElement à l'index spécifié. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Définit un accent (un caractère au-dessus de cet élément). |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Ajoute un élément mathématique à la fin de la collection. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Prend une fonction spécifiée en utilisant cette instance comme argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Prend une fonction spécifiée en utilisant cette instance comme argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Prend une fonction spécifiée en utilisant cette instance comme argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Prend une fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Prend une fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Supprime tous les éléments de la collection. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Détermine si la collection contient une valeur spécifique. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Copie dans un tableau spécifié. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Délimite les éléments enfants avec un caractère séparateur (sans les parenthèses). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crée une fraction avec ce numérateur et un dénominateur spécifié. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crée une fraction avec ce numérateur et un dénominateur spécifié. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et un dénominateur spécifié. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et un dénominateur spécifié. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Enclot un élément mathématique entre parenthèses. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Enclot les éléments enfants de ce bloc dans les caractères spécifiés tels que les parenthèses ou d'autres caractères comme encadrement. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Enclot les éléments enfants de ce bloc dans les caractères spécifiés tels que les parenthèses ou d'autres comme encadrement et délimite avec un caractère séparateur. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Obtient les éléments enfants. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Place cet élément dans un groupe en utilisant une accolade inférieure. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Place cet élément dans un groupe en utilisant un caractère de regroupement tel qu'une accolade inférieure ou un autre. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Détermine l'index d'un élément mathématique spécifique dans la collection. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Insère un MathElement dans la collection à l'index spécifié. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Prend l'intégrale sans limites. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Prend l'intégrale. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Prend l'intégrale. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Prend l'intégrale. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Prend l'intégrale. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Joint un élément mathématique avec ce bloc mathématique. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Joint un texte mathématique avec ce bloc mathématique. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Joint un autre bloc mathématique avec celui-ci. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crée un opérateur N-aire. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Crée un opérateur N-aire. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Définit une barre au-dessus de cet élément. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Supprime la première occurrence d'un objet spécifique de la collection. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Supprime l'élément à l'index spécifié de la collection. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Prend la limite inférieure. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Prend la limite inférieure. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crée un indice. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crée un indice. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crée un indice et un exposant à gauche. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crée un indice et un exposant à gauche. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crée un indice et un exposant à droite. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crée un indice et un exposant à droite. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crée un exposant. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crée un exposant. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Prend la limite supérieure. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Prend la limite supérieure. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Place cet élément dans une bordure. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Place cet élément dans une bordure. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Place cet élément dans une boîte non visible (regroupement logique) qui est utilisée pour regrouper des composants d'une équation ou une autre instance de texte mathématique. Un objet encapsulé peut (par exemple) servir d'émulateur d'opérateur avec ou sans point d'alignement, servir de point de rupture de ligne, ou être regroupé de manière à ne pas permettre des ruptures de ligne à l'intérieur. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Met les éléments enfants dans un tableau vertical. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Définit une barre en dessous de cet élément. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Enregistre le contenu de ce [`MathBlock`](../mathblock) en tant que MathML |

### Exemples

Exemple :

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Voir aussi

* class [MathElementBase](../mathelementbase)
* interface [IMathBlock](../imathblock)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->