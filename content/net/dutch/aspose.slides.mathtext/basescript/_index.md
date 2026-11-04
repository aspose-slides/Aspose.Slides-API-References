---
title: BaseScript
second_title: Aspose.Sildes voor .NET API-referentie
description: Wiskundescript
type: docs
weight: 8090
url: /nl/aspose.slides.mathtext/basescript/
---
## BaseScript klasse

Wiskundescript

```csharp
public abstract class BaseScript : MathElementBase
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | Basisargument |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Stelt een accentteken in (een teken boven dit element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Neemt de opgegeven functie waarbij deze instantie als argument en het opgegeven extra argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Neemt de opgegeven functie waarbij deze instantie als argument en het opgegeven extra argument wordt gebruikt |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Maakt een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Maakt een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omsluit een wiskundig element met haakjes |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Omsluit een wiskundig element met opgegeven tekens, zoals haakjes of andere tekens als kader |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Plaatst dit element in een groep met een onderste accolade |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Plaatst dit element in een groep met een groepeerteken zoals een onderste accolade of een ander teken |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Neemt de integraal zonder limieten |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Neemt de integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Neemt de integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Neemt de integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Neemt de integraal |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Voegt een wiskundige tekst samen en vormt een wiskundig blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Maakt een N-aire operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Maakt een N-aire operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Stelt een balk boven dit element in |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specificeert de wiskundige wortel van de opgegeven graad vanuit het opgegeven argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specificeert de wiskundige wortel van de opgegeven graad vanuit het opgegeven argument. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Neemt de onderlimiet |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Neemt de onderlimiet |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Maakt een subscript |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Maakt een subscript |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Maakt subscript en superscript aan de linkerkant |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Maakt subscript en superscript aan de linkerkant |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Maakt subscript en superscript aan de rechterkant |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Maakt subscript en superscript aan de rechterkant |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Maakt superscript |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Maakt superscript |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Neemt de bovengrens |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Neemt de bovengrens |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Plaatst dit element in een randvak |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Plaatst dit element in een randvak |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Plaatst dit element in een niet-visuele box (logische groepering) die wordt gebruikt om componenten van een vergelijking of een ander stuk wiskundige tekst te groeperen. Een ingeboxd object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, dienen als een regeleinde-punt, of worden gegroepeerd zodat geen regeleinden binnen toegestaan zijn. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Plaatst in een verticale rij |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Stelt een balk onder dit element in |

### Zie ook

* klasse [MathElementBase](../mathelementbase)
* naamruimte [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->