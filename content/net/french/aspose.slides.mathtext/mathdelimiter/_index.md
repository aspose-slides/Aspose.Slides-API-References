---
title: MathDelimiter
second_title: Référence API Aspose.Slides pour .NET
description: Spécifie l'objet délimiteur composé de caractères d'ouverture et de fermeture tels que des parenthèses, des accolades, des crochets et des barres verticales, et un ou plusieurs éléments mathématiques à l'intérieur, séparés par un caractère spécifié. Exemples  2 2x7C2
type: docs
weight: 8390
url: /fr/aspose.slides.mathtext/mathdelimiter/
---

## MathDelimiter class

Spécifie l'objet délimiteur, composé de caractères d'ouverture et de fermeture (tels que des parenthèses, des accolades, des crochets et des barres verticales), et un ou plusieurs éléments mathématiques à l'intérieur, séparés par un caractère spécifié. Exemples : (𝑥2) ; [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## Constructors

| Name | Description |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | Initialise MathDelimiter avec l'élément spécifié comme argument de base unique |

## Properties

| Name | Description |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | Un ou plusieurs éléments mathématiques séparés par des caractères de délimitation |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Le caractère de début du délimiteur spécifie le caractère de délimitation de début, ou d'ouverture. Les délimiteurs mathématiques sont des caractères d'encapsulation tels que des parenthèses, des crochets et des accolades. La valeur par défaut : '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | Spécifie la forme des délimiteurs dans l'objet délimiteur. Lorsque c'est MathDelimiterShape.Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique et peuvent encore être adaptés à toute la hauteur de leur contenu. Lorsque c'est MathDelimiterShape.Match, leur hauteur et leur forme sont modifiées pour correspondre exactement à leur contenu. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Le caractère de fin du délimiteur spécifie le caractère de délimitation de fin, ou de fermeture. Les délimiteurs mathématiques sont des caractères d'encapsulation tels que des parenthèses, des crochets et des accolades. La valeur par défaut : ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | Spécifie la croissance de BeginningCharacter, SeparatorCharacter, EndingCharacter. Lorsque true, les délimiteurs croissent verticalement pour correspondre à la hauteur de son opérande. La valeur par défaut est true. |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Le caractère de séparation du délimiteur spécifie le caractère qui sépare les arguments dans l'objet délimiteur. La valeur par défaut : '&#x7C;'. |

## Methods

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Définit un accent (un caractère sur le dessus de cet élément) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Prend la fonction spécifiée en utilisant cette instance comme argument et l'argument supplémentaire spécifié |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Prend la fonction spécifiée en utilisant cette instance comme argument et l'argument supplémentaire spécifié |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | Délimite les arguments en utilisant le caractère délimiteur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Encerclé un élément mathématique dans des parenthèses |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | Encerclé un élément mathématique dans des caractères spécifiés tels que des parenthèses ou d'autres caractères comme encadrement |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | Récupère les éléments enfants |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Place cet élément dans un groupe en utilisant une accolade inférieure |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Place cet élément dans un groupe en utilisant un caractère de groupement tel qu'une accolade inférieure ou autre |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Prend l'intégrale sans limites |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Prend l'intégrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Prend l'intégrale |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Joint un élément mathématique et forme un bloc mathématique |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Joint un texte mathématique et forme un bloc mathématique |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crée un opérateur N-aire |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Crée un opérateur N-aire |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Met une barre sur le dessus de cet élément |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Précise la racine mathématique du degré donné à partir de l'argument spécifié. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Précise la racine mathématique du degré donné à partir de l'argument spécifié. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Prend la limite inférieure |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Prend la limite inférieure |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crée un indice inférieur |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crée un indice inférieur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crée un indice inférieur et un indice supérieur à gauche |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crée un indice inférieur et un indice supérieur à gauche |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crée un indice inférieur et un indice supérieur à droite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crée un indice inférieur et un indice supérieur à droite |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crée un indice supérieur |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crée un indice supérieur |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Prend la limite supérieure |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Prend la limite supérieure |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Place cet élément dans une zone de bordure |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Place cet élément dans une zone de bordure |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Place cet élément dans une boîte non visible (groupement logique) qui est utilisée pour regrouper les composants d'une équation ou d'une autre instance de texte mathématique. Un objet encadré peut (par exemple) servir d'émulateur d'opérateur avec ou sans un point d'alignement, servir de point d'interruption de ligne, ou être groupé de manière à ne pas permettre des coupures de ligne à l'intérieur. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Met dans un tableau vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Met une barre au bas de cet élément |

### Examples

Exemple :

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### See Also

* class [MathElementBase](../mathelementbase)
* interface [IMathDelimiter](../imathdelimiter)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->