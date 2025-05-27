---
title: MathDelimiter
second_title: Référence de l'API Aspose.Slides pour .NET
description: Spécifie l'objet délimiteur composé de caractères d'ouverture et de fermeture tels que parenthèses, accolades, crochets et barres verticales, et un ou plusieurs éléments mathématiques à l'intérieur, séparés par un caractère spécifié. Exemples : 2 2x7C2
type: docs
weight: 8390
url: /fr/aspose.slides.mathtext/mathdelimiter/
---

## Classe MathDelimiter

Spécifie l'objet délimiteur, composé de caractères d'ouverture et de fermeture (tels que parenthèses, accolades, crochets et barres verticales), et un ou plusieurs éléments mathématiques à l'intérieur, séparés par un caractère spécifié. Exemples : (𝑥2) ; [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## Constructeurs

| Nom                                               | Description                                                                            |
|--------------------------------------------------|----------------------------------------------------------------------------------------|
| [MathDelimiter](mathdelimiter)(IMathElement)     | Initialise MathDelimiter avec l'élément spécifié comme argument de base unique       |

## Propriétés

| Nom                                                         | Description                                                                                                        |
|------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; }                      | Un ou plusieurs éléments mathématiques séparés par des caractères délimiteurs                                      |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Le caractère de début du délimiteur spécifie le caractère délimiteur d'ouverture. Les délimiteurs mathématiques sont des caractères englobants tels que des parenthèses, des crochets et des accolades. Par défaut : '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; }        | Spécifie la forme des délimiteurs dans l'objet délimiteur. Lorsque c'est MathDelimiterShape.Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique et peuvent encore être ajustés pour s'adapter à la hauteur totale de leur contenu. Lorsque c'est MathDelimiterShape.Match, leur hauteur et leur forme sont modifiées pour correspondre exactement à leur contenu. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; }      | Le caractère de fin du délimiteur spécifie le caractère délimiteur de fin. Les délimiteurs mathématiques sont des caractères englobants tels que des parenthèses, des crochets et des accolades. Par défaut : ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | Spécifie la croissance du BeginningCharacter, SeparatorCharacter, EndingCharacter. Lorsqu'il est vrai, les délimiteurs se développent verticalement pour correspondre à la hauteur de son opérande. La valeur par défaut est vraie. |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Le caractère de séparation du délimiteur spécifie le caractère qui sépare les arguments dans l'objet délimiteur. Par défaut : '&#x7C;'. |

## Méthodes

| Nom                                                         | Description                                                                            |
|------------------------------------------------------------|----------------------------------------------------------------------------------------|
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char)                                   | Définit un accent (un caractère au-dessus de cet élément)                               |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Prend une fonction spécifiée utilisant cette instance comme argument                   |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Prend une fonction spécifiée utilisant cette instance comme argument                   |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string)    | Prend une fonction spécifiée utilisant cette instance comme argument                   |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Prend une fonction spécifiée utilisant cette instance comme argument et l'argument supplémentaire spécifié |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Prend une fonction spécifiée utilisant cette instance comme argument et l'argument supplémentaire spécifié |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char)                                   | Délimite les arguments en utilisant le caractère délimiteur spécifié                  |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement)                           | Crée une fraction avec ce numérateur et le dénominateur spécifié                      |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string)                                 | Crée une fraction avec ce numérateur et le dénominateur spécifié                      |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes)       | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié    |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes)             | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié    |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)()                                     | Enclot un élément mathématique dans des parenthèses                                      |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char)        | Enclot un élément mathématique dans des caractères spécifiés tels que des parenthèses ou d'autres caractères comme cadre |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement)                       | Prend une fonction d'un argument en utilisant cette instance comme nom de la fonction  |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string)                             | Prend une fonction d'un argument en utilisant cette instance comme nom de la fonction  |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)()                               | Obtient les éléments enfants                                                              |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)()                                        | Place cet élément dans un groupe en utilisant une accolade courbée inférieure            |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Place cet élément dans un groupe en utilisant un caractère de regroupement tel qu'une accolade courbée inférieure ou autre |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes)                 | Prend l'intégrale sans limites                                                              |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Prend l'intégrale                                                                          |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Prend l'intégrale                                                                          |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Prend l'intégrale                                                                          |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Prend l'intégrale                                                                          |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement)                       | Joint un élément mathématique et forme un bloc mathématique                                |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string)                             | Joint un texte mathématique et forme un bloc mathématique                                    |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crée un opérateur N-aire                                                                    |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string)  | Crée un opérateur N-aire                                                                    |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)()                                   | Définit une barre au-dessus de cet élément                                                  |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement)                        | Spécifie la racine mathématique de degré donné à partir de l'argument spécifié.               |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string)                             | Spécifie la racine mathématique de degré donné à partir de l'argument spécifié.               |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement)          | Prend la limite inférieure                                                                    |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string)                | Prend la limite inférieure                                                                    |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement)            | Crée un indice inférieur                                                                     |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string)                  | Crée un indice inférieur                                                                     |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crée un indice inférieur et un exposant à gauche                                      |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crée un indice inférieur et un exposant à gauche                                      |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crée un indice inférieur et un exposant à droite                                         |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crée un indice inférieur et un exposant à droite                                         |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement)        | Crée un exposant                                                                          |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string)              | Crée un exposant                                                                          |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement)          | Prend la limite supérieure                                                                    |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string)                | Prend la limite supérieure                                                                    |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)()                         | Place cet élément dans une boîte de bordure                                               |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Place cet élément dans une boîte de bordure                                               |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)()                                     | Place cet élément dans une boîte non visuelle (groupement logique) utilisée pour grouper les composants d'une équation ou d'autres instances de texte mathématique. Un objet encadré peut (par exemple) servir d'émulateur d'opérateur avec ou sans point d'alignement, servir de point de saut de ligne, ou être groupé de manière à ne pas autoriser les sauts de ligne à l'intérieur. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)()                  | Met dans un tableau vertical                                                                 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)()                               | Définit une barre en bas de cet élément                                                    |

### Exemples

Exemple :

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### Voir aussi

* classe [MathElementBase](../mathelementbase)
* interface [IMathDelimiter](../imathdelimiter)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->