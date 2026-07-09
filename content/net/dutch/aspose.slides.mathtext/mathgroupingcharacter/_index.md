---
title: MathGroupingCharacter
second_title: Aspose.Sildes voor .NET API-referentie
description: Specificeert een groepsymbool boven of onder een expressie, meestal om de relatie tussen elementen te benadrukken
type: docs
weight: 8760
url: /nl/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter klasse

Specificeert een groepsymbool boven of onder een expressie, meestal om de relatie tussen elementen te benadrukken.

```csharp
public sealed class MathGroupingCharacter : MathElementBase, IMathGroupingCharacter
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [MathGroupingCharacter](mathgroupingcharacter#constructor)(IMathElement) | Initialiseert een nieuw exemplaar van de MathGroupingCharacter klasse met het standaard groepsymbool U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter](mathgroupingcharacter#constructor_1)(IMathElement, char, MathTopBotPositions, MathTopBotPositions) | Initialiseert een nieuw exemplaar van de MathGroupingCharacter klasse. |

## Properties

| Naam | Beschrijving |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathgroupingcharacter/base) { get; } | Basisargument |
| [Character](../../aspose.slides.mathtext/mathgroupingcharacter/character) { get; set; } | Groepskarakter Standaardwaarde: U+23DF (BOTTOM CURLY BRACKET) |
| [Position](../../aspose.slides.mathtext/mathgroupingcharacter/position) { get; set; } | Positie van het groepsymbool. Standaard: Bottom |
| [VerticalJustification](../../aspose.slides.mathtext/mathgroupingcharacter/verticaljustification) { get; set; } | Verticale uitlijning van het groepsymbool. Bepaalt de uitlijning van het object ten opzichte van de basislijn. Bijvoorbeeld, wanneer het groepsymbool zich boven het object bevindt, geeft VerticalJustification van Top aan dat de bovenkant van het object op de basislijn ligt; wanneer VerticalJustification is ingesteld op Bottom, ligt de onderkant van het object op de basislijn Standaard: Bottom voor Position=Top, en Top voor Position=Bottom |

## Methods

| Naam | Beschrijving |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Stelt een accentteken in (een teken boven dit element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Neemt een opgegeven functie waarbij dit exemplaar als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Neemt een opgegeven functie waarbij dit exemplaar als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Neemt een opgegeven functie waarbij dit exemplaar als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Neemt een opgegeven functie waarbij dit exemplaar als argument wordt gebruikt en een opgegeven extra argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Neemt een opgegeven functie waarbij dit exemplaar als argument wordt gebruikt en een opgegeven extra argument |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Maakt een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Maakt een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omsluit een wiskundig element met haakjes |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Omsluit een wiskundig element met opgegeven tekens, zoals haakjes of andere tekens als omkadering |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Neemt een functie van een argument waarbij dit exemplaar als functienaam wordt gebruikt |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Neemt een functie van een argument waarbij dit exemplaar als functienaam wordt gebruikt |
| [GetChildren](../../aspose.slides.mathtext/mathgroupingcharacter/getchildren)() | Verkrijgt kindelementen |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Plaatst dit element in een groep met een onderste krullende haak |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Plaatst dit element in een groep met een groepsymbool, zoals een onderste krullende haak of een ander |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Neemt de integraal zonder grenzen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Neemt de integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Neemt de integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Neemt de integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Neemt de integraal |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Voegt een wiskundig tekstfragment samen en vormt een wiskundig blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Maakt een N-aire operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Maakt een N-aire operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Stelt een balk boven dit element in |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specificeert de wiskundige wortel van de opgegeven graad vanuit het gespecificeerde argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specificeert de wiskundige wortel van de opgegeven graad vanuit het gespecificeerde argument. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Neemt onderlimiet |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Neemt onderlimiet |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Maakt subscript |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Maakt subscript |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Maakt subscript en superscript links |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Maakt subscript en superscript links |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Maakt subscript en superscript rechts |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Maakt subscript en superscript rechts |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Maakt superscript |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Maakt superscript |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Neemt bovenlimiet |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Neemt bovenlimiet |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Plaatst dit element in een randvak |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Plaatst dit element in een randvak |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Plaatst dit element in een niet-visuele doos (logische groepering) die wordt gebruikt om componenten van een vergelijking of ander wiskundig tekstfragment te groeperen. Een ingekaderd object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder uitlijningspunt, dienen als een regeleinde punt, of gegroepeerd worden zodat geen regeleinden binnen toegestaan zijn. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Plaatst in een verticale array |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Stelt een balk onder dit element in |

### Voorbeelden

Example:

```csharp
[C#]
MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```

### Zie ook

* klasse [MathElementBase](../mathelementbase)
* interface [IMathGroupingCharacter](../imathgroupingcharacter)
* naamruimte [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->