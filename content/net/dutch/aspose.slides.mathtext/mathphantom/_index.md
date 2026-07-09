---
title: MathPhantom
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een phantom-wiskunde-object ltmphantgt voor dat de lay-out van het onderliggende element beïnvloedt zonder dat het noodzakelijk wordt weergegeven. Een phantom kan de basis-expressie verbergen terwijl de breedte, hoogte of diepte behouden blijven om formules uit te lijnen of ruimte te reserveren. Zichtbaarheid en geometrisch gedrag worden gecontroleerd door eigenschappen zoals Show, ZeroWid, ZeroAsc, ZeroDesc en Transp.
type: docs
weight: 8920
url: /nl/aspose.slides.mathtext/mathphantom/
---
## MathPhantom klasse

Stelt een phantom-wiskunde-object (&lt;m:phant&gt;) voor dat de lay-out van het onderliggende element beïnvloedt zonder dat het noodzakelijk wordt weergegeven. Een phantom kan de basis-expressie verbergen terwijl de breedte, hoogte of diepte behouden blijven om formules uit te lijnen of ruimte te reserveren. Zichtbaarheid en geometrisch gedrag worden gecontroleerd door eigenschappen zoals Show, ZeroWid, ZeroAsc, ZeroDesc en Transp.

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## Constructoren

| Naam | Beschrijving |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | Initialiseert een nieuw exemplaar van de [`MathPhantom`](../mathphantom) klasse met het opgegeven basiselement. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | Basisargument |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft of het basiselement wordt weergegeven. |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft of de phantom transparant is voor klassen-gebaseerde spatiëringsregels. |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft of de stijging (hoogte boven de basislijn) van het basiselement als nul moet worden behandeld. |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft of de daling (diepte onder de basislijn) van het basiselement als nul moet worden behandeld. |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft of de breedte van het basiselement als nul moet worden behandeld. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Stelt een accentteken in (een teken boven dit element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Neemt de opgegeven functie met dit exemplaar als argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Neemt de opgegeven functie met dit exemplaar als argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Neemt de opgegeven functie met dit exemplaar als argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Neemt de opgegeven functie met dit exemplaar als argument en een extra opgegeven argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Neemt de opgegeven functie met dit exemplaar als argument en een extra opgegeven argument |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Maakt een breuk met dit teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Maakt een breuk met dit teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Maakt een breuk van het opgegeven type met dit teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Maakt een breuk van het opgegeven type met dit teller en de opgegeven noemer |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Plaatst een wiskundig element tussen haakjes |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Plaatst een wiskundig element tussen opgegeven tekens, zoals haakjes of andere tekens als omlijsting |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Neemt een functie van een argument met dit exemplaar als functienaam |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Neemt een functie van een argument met dit exemplaar als functienaam |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | Haalt onderliggende elementen op |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Plaatst dit element in een groep met een onderste accolade |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Plaatst dit element in een groep met een groepeerteken, zoals een onderste accolade of een ander teken |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Neemt de integraal zonder grenzen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Neemt de integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Neemt de integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Neemt de integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Neemt de integraal |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Verbindt een wiskundig element en vormt een wiskundig blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Verbindt een wiskundige tekst en vormt een wiskundig blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Creëert een N-airy-operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Creëert een N-airy-operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Plaatst een balk boven dit element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specificeert de wiskundige wortel van de opgegeven graad vanuit het opgegeven argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specificeert de wiskundige wortel van de opgegeven graad vanuit het opgegeven argument. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Neemt ondergrens |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Neemt ondergrens |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Plaatst dit element in een rand-box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Plaatst dit element in een rand-box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Plaatst dit element in een niet-visuele box (logische groepering) die wordt gebruikt om componenten van een vergelijking of andere wiskundige tekst te groeperen. Een ingekaderd object kan (bijvoorbeeld) dienen als operator-emulator met of zonder uitlijningspunt, als regeleinde-punt, of gegroepeerd worden zodat er geen regeleinden binnen vallen. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Plaatst in een verticale rij |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Plaatst een balk onder dit element |

### Voorbeelden

Voorbeeld:

```csharp
[C#]
IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // Verberg de inhoud
phantom.ZeroWidth = false;     // Bewaar de breedte
```

### Zie ook

* klasse [MathElementBase](../mathelementbase)
* interface [IMathPhantom](../imathphantom)
* naamruimte [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->