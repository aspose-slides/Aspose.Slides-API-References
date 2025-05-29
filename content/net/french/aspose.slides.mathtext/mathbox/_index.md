---
title: MathBox
second_title: Référence de l'API Aspose.Slides pour .NET
description: Spécifie l'encapsulation logique des éléments mathématiques. Par exemple, un objet encadré peut servir d'émulateur d'opérateur avec ou sans point d'alignement, servir de point de saut de ligne, ou être regroupé de manière à ne pas permettre de sauts de ligne à l'intérieur. Par exemple, l'opérateur "==" devrait être encadré pour empêcher les sauts de ligne.
type: docs
weight: 8370
url: /fr/aspose.slides.mathtext/mathbox/
---

## Classe MathBox

Spécifie l'encapsulation logique (conditionnement) des éléments mathématiques. Par exemple, un objet encadré peut servir d'émulateur d'opérateur avec ou sans point d'alignement, servir de point de saut de ligne, ou être regroupé de manière à ne pas permettre de sauts de ligne à l'intérieur. Par exemple, l'opérateur "==" devrait être encadré pour empêcher les sauts de ligne.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Initialise MathBox avec l'élément spécifié en tant qu'argument |

## Propriétés

| Nom | Description |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Lorsqu'il est vrai, cet émulateur d'opérateur sert de point d'alignement ; c'est-à-dire que les points d'alignement désignés dans d'autres équations peuvent être alignés avec lui. Par défaut : faux |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Argument de base |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Différentiel Lorsqu'il est vrai, la boîte agit comme un différentiel (par exemple, 𝑑𝑥 dans un intégrande), et reçoit l'espacement horizontal approprié pour le différentiel mathématique. Par défaut : faux |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | La rupture explicite spécifie s'il y a un saut de ligne au début de l'objet Box, de sorte que la ligne se plie au début de l'objet box. Elle spécifie le numéro de l'opérateur sur la ligne précédente de texte mathématique qui doit être utilisé comme point d'alignement pour la ligne actuelle de texte mathématique. Valeurs possibles : 1..255 Par défaut : 0 (pas de rupture explicite) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Pas de rupture Cette propriété spécifie la propriété "ininterrompue" sur l'objet de la boîte. Lorsqu'il est vrai, aucun saut de ligne ne peut se produire à l'intérieur de la boîte. Cela peut être important pour les émulateurs d'opérateurs qui consistent en plus d'un opérateur binaire. Lorsque cet élément n'est pas spécifié, des ruptures peuvent se produire à l'intérieur de la boîte. Par défaut : vrai |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Émulateur d'opérateur. Lorsqu'il est vrai, la boîte et son contenu se comportent comme un seul opérateur et héritent des propriétés d'un opérateur. Cela signifie, par exemple, que le caractère peut servir de point pour un saut de ligne et peut être aligné avec d'autres opérateurs. Les émulateurs d'opérateurs sont souvent utilisés lorsqu'un ou plusieurs glyphes se combinent pour former un opérateur, tel que '=='. Valeur par défaut : faux |

## Méthodes

| Nom | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Définit un accent (un caractère en haut de cet élément) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Enclot un élément mathématique entre parenthèses |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Enclot un élément mathématique dans des caractères spécifiés tels que des parenthèses ou d'autres caractères comme cadre |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Obtenir les éléments enfants |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Place cet élément dans un groupe à l'aide d'une accolade inférieure |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Place cet élément dans un groupe à l'aide d'un caractère de regroupement tel qu'une accolade inférieure ou autre |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Prend l'intégrale sans limites |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Prend l'intégrale |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Joint un élément mathématique et forme un bloc mathématique |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Joint un texte mathématique et forme un bloc mathématique |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crée un opérateur N-arité |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Crée un opérateur N-arité |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Met une barre en haut de cet élément |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Place cet élément dans une boîte de bordure |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Place cet élément dans une boîte de bordure |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Place cet élément dans une boîte non visuelle (regroupement logique) qui est utilisée pour regrouper les composants d'une équation ou d'une autre instance de texte mathématique. Un objet encadré peut (par exemple) servir d'émulateur d'opérateur avec ou sans point d'alignement, servir de point de saut de ligne, ou être regroupé de manière à ne pas permettre de sauts de ligne à l'intérieur. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Met dans un tableau vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Met une barre en bas de cet élément |

### Exemples

Exemple:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Voir aussi

* classe [MathElementBase](../mathelementbase)
* interface [IMathBox](../imathbox)
* espace de noms [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
