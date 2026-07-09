---
title: MathNaryOperator
second_title: Aspose.Sildes voor .NET API Referentie
description: Specificeert een N-aire wiskundig object, zoals Summation en Integral. Het bestaat uit een operator, een base of operand en optionele boven- en onderlimieten. Voorbeelden van N-aire operatoren zijn Summation, Union, Intersection, Integral
type: docs
weight: 8870
url: /nl/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator klasse

Bepaalt een N-aire wiskundig object, zoals Summation en Integral. Het bestaat uit een operator, een basis (of operand), en optionele boven- en onderlimieten. Voorbeelden van N-aire operatoren zijn: Summation, Union, Intersection, Integral

```csharp
public sealed class MathNaryOperator : MathElementBase, IMathNaryOperator
```

## Constructoren

| Naam | Beschrijving |
| --- | --- |
| [MathNaryOperator](mathnaryoperator#constructor)(char, IMathElement) | Initialiseert een nieuw exemplaar van de MathNaryOperator klasse. |
| [MathNaryOperator](mathnaryoperator#constructor_1)(char, IMathElement, IMathElement) | Initialiseert een nieuw exemplaar van de MathNaryOperator klasse. |
| [MathNaryOperator](mathnaryoperator#constructor_2)(char, IMathElement, IMathElement, IMathElement) | Initialiseert een nieuw exemplaar van de MathNaryOperator klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathnaryoperator/base) { get; } | Basisargument |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathnaryoperator/growtomatchoperandheight) { get; set; } | Operator-teken groeit verticaal om zijn operandhoogte te evenaren |
| [HideSubscript](../../aspose.slides.mathtext/mathnaryoperator/hidesubscript) { get; set; } | Verberg subscript |
| [HideSuperscript](../../aspose.slides.mathtext/mathnaryoperator/hidesuperscript) { get; set; } | Verberg superscript |
| [LimitLocation](../../aspose.slides.mathtext/mathnaryoperator/limitlocation) { get; set; } | De locatie van limieten (subscript en superscript) |
| [Operator](../../aspose.slides.mathtext/mathnaryoperator/operator) { get; set; } | N-aire operator-teken Bijvoorbeeld: '∑', '∫' |
| [Subscript](../../aspose.slides.mathtext/mathnaryoperator/subscript) { get; } | Specificeert een subscript-argument dat, bijvoorbeeld in het geval van een Integral, de onderlimiet instelt |
| [Superscript](../../aspose.slides.mathtext/mathnaryoperator/superscript) { get; } | Specificeert een superscript-argument dat, bijvoorbeeld in het geval van een Integral, de bovengrens instelt |

## Methodes

| Naam | Beschrijving |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Stelt een accentteken in (een teken boven dit element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Neemt de opgegeven functie waarbij dit exemplaar als argument en een gespecificeerd extra argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Neemt de opgegeven functie waarbij dit exemplaar als argument en een gespecificeerd extra argument wordt gebruikt |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Creëert een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Creëert een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Creëert een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Creëert een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omringt een wiskundig element met haakjes |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Omringt een wiskundig element met opgegeven tekens, zoals haakjes of andere tekens als omlijsting |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Neemt een functie van een argument waarbij dit exemplaar als functienaam wordt gebruikt |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Neemt een functie van een argument waarbij dit exemplaar als functienaam wordt gebruikt |
| [GetChildren](../../aspose.slides.mathtext/mathnaryoperator/getchildren)() | Haalt onderliggende elementen op |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Plaatst dit element in een groep met behulp van een onderste accolade |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Plaatst dit element in een groep met een groepeerteken, zoals een onderste accolade of een ander teken |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Neemt de Integral zonder limieten |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Neemt de Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Neemt de Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Neemt de Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Neemt de Integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Voegt een wiskundige tekst samen en vormt een wiskundig blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Creëert een N-aire operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Creëert een N-aire operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Stelt een balk bovenaan dit element in |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specificeert de wiskundige wortel van de gegeven graad vanuit het opgegeven argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specificeert de wiskundige wortel van de gegeven graad vanuit het opgegeven argument. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Neemt onderlimiet |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Neemt onderlimiet |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Creëert subscript |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Creëert subscript |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Creëert subscript en superscript links |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Creëert subscript en superscript links |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Creëert subscript en superscript rechts |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Creëert subscript en superscript rechts |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Creëert superscript |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Creëert superscript |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Neemt bovengrens |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Neemt bovengrens |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Plaatst dit element in een randvak |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Plaatst dit element in een randvak |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Plaatst dit element in een niet-visueel vak (logische groepering) dat wordt gebruikt om componenten van een vergelijking of andere instantie van wiskundige tekst te groeperen. Een ingekapseld object kan (bijvoorbeeld) dienen als operator-emulator met of zonder uitlijningspunt, dienen als een regeleinde-punt, of gegroepeerd worden zodat geen regeleinden binnen worden toegestaan. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Plaats in een verticale reeks |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Stelt een balk onderaan dit element in |

### Voorbeelden

Voorbeeld:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### Zie ook

* klasse [MathElementBase](../mathelementbase)
* interface [IMathNaryOperator](../imathnaryoperator)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->