---
title: MathNaryOperator
second_title: Aspose.Slides pour .NET Référence API
description: Spécifie un objet mathématique N-aire tel que Somme et Intégrale. Il se compose d'un opérateur, d'une base ou opérande et de limites supérieures et inférieures optionnelles. Exemples d'opérateurs N-aires  Somme, Union, Intersection, Intégrale
type: docs
weight: 8610
url: /fr/aspose.slides.mathtext/mathnaryoperator/
---

## MathNaryOperator class

Spécifie un objet mathématique N-aire, tel que Somme et Intégrale. Il se compose d'un opérateur, d'une base (ou opérande) et de limites supérieures et inférieures optionnelles. Exemples d'opérateurs N-aires : Somme, Union, Intersection, Intégrale

```csharp
public sealed class MathNaryOperator : MathElementBase, IMathNaryOperator
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MathNaryOperator](mathnaryoperator#constructor)(char, IMathElement) | Initialise une nouvelle instance de la classe MathNaryOperator. |
| [MathNaryOperator](mathnaryoperator#constructor_1)(char, IMathElement, IMathElement) | Initialise une nouvelle instance de la classe MathNaryOperator. |
| [MathNaryOperator](mathnaryoperator#constructor_2)(char, IMathElement, IMathElement, IMathElement) | Initialise une nouvelle instance de la classe MathNaryOperator. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathnaryoperator/base) { get; } | Argument de base |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathnaryoperator/growtomatchoperandheight) { get; set; } | Le caractère de l'opérateur grandit verticalement pour correspondre à la hauteur de son opérande |
| [HideSubscript](../../aspose.slides.mathtext/mathnaryoperator/hidesubscript) { get; set; } | Masquer le sous-script |
| [HideSuperscript](../../aspose.slides.mathtext/mathnaryoperator/hidesuperscript) { get; set; } | Masquer le super-script |
| [LimitLocation](../../aspose.slides.mathtext/mathnaryoperator/limitlocation) { get; set; } | La localisation des limites (sous-script et super-script) |
| [Operator](../../aspose.slides.mathtext/mathnaryoperator/operator) { get; set; } | Caractère de l'opérateur N-aire Par exemple : '∑', '∫' |
| [Subscript](../../aspose.slides.mathtext/mathnaryoperator/subscript) { get; } | Spécifie un argument de sous-script qui, par exemple, dans le cas d'une intégrale, définit la limite inférieure |
| [Superscript](../../aspose.slides.mathtext/mathnaryoperator/superscript) { get; } | Spécifie un argument de super-script qui, par exemple, dans le cas d'une intégrale, définit la limite supérieure |

## Méthodes

| Nom | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Définit un accent (un caractère sur le dessus de cet élément) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Enveloppe un élément mathématique dans des parenthèses |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Enveloppe un élément mathématique dans des caractères spécifiés tels que des parenthèses ou d'autres caractères de cadre |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [GetChildren](../../aspose.slides.mathtext/mathnaryoperator/getchildren)() | Obtenir des éléments enfants |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Place cet élément dans un groupe en utilisant une accolade courbe inférieure |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Place cet élément dans un groupe en utilisant un caractère de regroupement tel qu'une accolade courbe inférieure ou un autre |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Prend l'intégrale sans limites |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Prend l'intégrale |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Joint un élément mathématique et forme un bloc mathématique |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Joint un texte mathématique et forme un bloc mathématique |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crée un opérateur N-aire |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Crée un opérateur N-aire |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Définit une barre sur le dessus de cet élément |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Prend la limite inférieure |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Prend la limite inférieure |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crée un sous-script |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crée un sous-script |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crée un sous-script et un super-script à gauche |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crée un sous-script et un super-script à gauche |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crée un sous-script et un super-script à droite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crée un sous-script et un super-script à droite |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crée un super-script |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crée un super-script |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Prend la limite supérieure |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Prend la limite supérieure |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Place cet élément dans une boîte de bordure |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Place cet élément dans une boîte de bordure |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Place cet élément dans une boîte non visible (regroupement logique) utilisée pour regrouper des composants d'une équation ou d'un autre instance de texte mathématique. Un objet encadré peut (par exemple) servir d'émulateur d'opérateur avec ou sans point d'alignement, servir de point de saut de ligne, ou être groupé de manière à ne pas permettre de sauts de ligne à l'intérieur. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Met dans un tableau vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Définit une barre au bas de cet élément |

### Exemples

Exemple :

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### Voir aussi

* class [MathElementBase](../mathelementbase)
* interface [IMathNaryOperator](../imathnaryoperator)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->