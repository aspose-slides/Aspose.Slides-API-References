---
title: MathGroupingCharacter
second_title: Référence de l'API Aspose.Slides pour .NET
description: Spécifie un symbole de regroupement au-dessus ou en dessous d'une expression, généralement pour mettre en évidence la relation entre les éléments
type: docs
weight: 8500
url: /fr/aspose.slides.mathtext/mathgroupingcharacter/
---

## Classe MathGroupingCharacter

Spécifie un symbole de regroupement au-dessus ou en dessous d'une expression, généralement pour mettre en évidence la relation entre les éléments.

```csharp
public sealed class MathGroupingCharacter : MathElementBase, IMathGroupingCharacter
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MathGroupingCharacter](mathgroupingcharacter#constructor)(IMathElement) | Initialise une nouvelle instance de la classe MathGroupingCharacter avec le caractère de regroupement par défaut U+23DF (ACCOLADE CURVÉE INFÉRIEURE) |
| [MathGroupingCharacter](mathgroupingcharacter#constructor_1)(IMathElement, char, MathTopBotPositions, MathTopBotPositions) | Initialise une nouvelle instance de la classe MathGroupingCharacter. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathgroupingcharacter/base) { get; } | Argument de base |
| [Character](../../aspose.slides.mathtext/mathgroupingcharacter/character) { get; set; } | Caractère de regroupement Valeur par défaut : U+23DF (ACCOLADE CURVÉE INFÉRIEURE) |
| [Position](../../aspose.slides.mathtext/mathgroupingcharacter/position) { get; set; } | Position du caractère de regroupement. Par défaut : Bas |
| [VerticalJustification](../../aspose.slides.mathtext/mathgroupingcharacter/verticaljustification) { get; set; } | Justification verticale du caractère de groupe. Spécifie l'alignement de l'objet par rapport à la base. Par exemple, lorsque le caractère de groupe est au-dessus de l'objet, la justification verticale en haut signifie que le haut de l'objet tombe sur la ligne de base ; lorsque la justification verticale est définie sur Bas, le bas de l'objet est sur la ligne de base. Valeur par défaut : Bas pour Position=Haut, et Haut pour Position=Bas |

## Méthodes

| Nom | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Définit un accent (un caractère sur le dessus de cet élément) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Prend la fonction spécifiée en utilisant cette instance comme argument et argument supplémentaire spécifié |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Prend la fonction spécifiée en utilisant cette instance comme argument et argument supplémentaire spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Enclot un élément mathématique entre parenthèses |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Enclot un élément mathématique avec des caractères spécifiés tels que des parenthèses ou d'autres caractères en tant que cadre |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Prend une fonction d'un argument en utilisant cette instance comme le nom de la fonction |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Prend une fonction d'un argument en utilisant cette instance comme le nom de la fonction |
| [GetChildren](../../aspose.slides.mathtext/mathgroupingcharacter/getchildren)() | Obtient les éléments enfants |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Place cet élément dans un groupe en utilisant une accolade courbée inférieure |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Place cet élément dans un groupe en utilisant un caractère de regroupement tel qu'une accolade courbée inférieure ou un autre |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Prend l'intégrale sans limites |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Prend l'intégrale |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Joint un élément mathématique et forme un bloc mathématique |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Joint un texte mathématique et forme un bloc mathématique |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crée un opérateur N-aire |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Crée un opérateur N-aire |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Définir une barre au-dessus de cet élément |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Prend la limite inférieure |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Prend la limite inférieure |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crée un indice inférieur |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crée un indice inférieur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crée un indice inférieur et un exposant à gauche |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crée un indice inférieur et un exposant à gauche |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crée un indice inférieur et un exposant à droite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crée un indice inférieur et un exposant à droite |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crée un exposant |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crée un exposant |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Prend la limite supérieure |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Prend la limite supérieure |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Place cet élément dans une boîte de bordure |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Place cet élément dans une boîte de bordure |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Place cet élément dans une boîte non visuelle (regroupement logique) qui est utilisée pour regrouper les composants d'une équation ou d'une autre instance de texte mathématique. Un objet encadré peut (par exemple) servir d'émulateur d'opérateur avec ou sans point d'alignement, servir de point de rupture de ligne, ou être groupé de manière à ne pas permettre de retours à la ligne à l'intérieur. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Met dans un tableau vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Définit une barre en dessous de cet élément |

### Exemples

Exemple :

```csharp
[C#]
MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```

### Voir aussi

* classe [MathElementBase](../mathelementbase)
* interface [IMathGroupingCharacter](../imathgroupingcharacter)
* espace de noms [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->