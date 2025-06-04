---
title: IMathElement
second_title: Aspose.Slides pour .NET Référence de l'API
description: Interface de base de tout élément mathématique  fraction, texte mathématique, fonction, expression avec plusieurs éléments, etc.
type: docs
weight: 7980
url: /fr/aspose.slides.mathtext/imathelement/
---

## Interface IMathElement

Interface de base de tout élément mathématique : fraction, texte mathématique, fonction, expression avec plusieurs éléments, etc.

```csharp
public interface IMathElement
```

## Méthodes

| Nom | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Définit une accentuation (un caractère au-dessus de cet élément) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Prend la fonction spécifiée en utilisant cette instance comme argument et l'argument supplémentaire spécifié |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Prend la fonction spécifiée en utilisant cette instance comme argument et l'argument supplémentaire spécifié |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Enclot un élément mathématique entre parenthèses |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Enclot cet élément dans les caractères spécifiés tels que parenthèses ou d'autres caractères comme cadre |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Récupère les éléments enfants |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Place cet élément dans un groupe utilisant une accolade inférieure |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Place cet élément dans un groupe utilisant un caractère de regroupement tel qu'une accolade inférieure ou autre |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Prend l'intégrale sans limites |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Prend l'intégrale |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Joint un élément mathématique et forme un bloc mathématique |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Joint un texte mathématique et forme un bloc mathématique |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crée un opérateur N-aire |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Crée un opérateur N-aire |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Définit une barre au-dessus de cet élément |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Spécifie la racine mathématique de degré donné à partir de l'argument spécifié. |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Spécifie la racine mathématique de degré donné à partir de l'argument spécifié. |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Prend la limite inférieure |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Prend la limite inférieure |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Crée un indice |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Crée un indice |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crée un indice et un exposant à gauche |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Crée un indice et un exposant à gauche |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Crée un indice et un exposant à droite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Crée un indice et un exposant à droite |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Crée un exposant |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Crée un exposant |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Prend la limite supérieure |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Prend la limite supérieure |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Place cet élément dans une boîte avec bord |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Place cet élément dans une boîte avec bord |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Place cet élément dans une boîte non visuelle (groupement logique) qui est utilisée pour grouper des composants d'une équation ou d'autres instances de texte mathématique. Un objet encadré peut (par exemple) servir d'émulateur d'opérateur avec ou sans un point d'alignement, servir de point de saut de ligne, ou être groupé de manière à ne pas permettre de sauts de ligne à l'intérieur. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Met dans un tableau vertical |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Définit une barre au-dessous de cet élément |

### Exemples

Exemple:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Voir aussi

* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->