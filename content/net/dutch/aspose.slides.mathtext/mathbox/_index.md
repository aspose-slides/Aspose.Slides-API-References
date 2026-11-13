---
title: MathBox
second_title: Aspose.Sildes voor .NET API-referentie
description: Specificeert de logische boxing verpakking van een wiskundig element. Een verpakt object kan bijvoorbeeld dienen als een operator-emulator met of zonder een uitlijningspunt, dienen als een regeleinde-punt, of worden gegroepeerd zodat regeleinden binnen niet worden toegestaan. Bijvoorbeeld moet de  operator verpakt worden om regeleinden te voorkomen.
type: docs
weight: 8650
url: /nl/aspose.slides.mathtext/mathbox/
---
## MathBox klasse

Specificeert de logische verpakken (boxing) van een wiskundig element. Een verpakt object kan bijvoorbeeld dienen als een operator-emulator met of zonder een uitlijningspunt, kan dienen als een regeleinde-punt, of kan gegroepeerd worden zodat er geen regeleinden binnen worden toegestaan. Bijvoorbeeld, de "==" operator moet verpakt worden om regeleinden te voorkomen.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Initialiseert MathBox met het opgegeven element als argument |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Wanneer true, dient deze operator-emulator als een uitlijningspunt; dat wil zeggen, aangewezen uitlijningspunten in andere vergelijkingen kunnen daarmee worden uitgelijnd. Standaard: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Basisargument |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Differentiaal. Wanneer true, werkt de box als een differentiaal (bijv. 𝑑𝑥 in een integrand), en krijgt de juiste horizontale spatiëring voor het wiskundige differentiaal. Standaard: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box-object, zodat de regel wordt afgebroken bij het begin van het box-object. Geeft het nummer van de operator op de vorige regel wiskundige tekst die moet worden gebruikt als uitlijningspunt voor de huidige regel wiskundige tekst. Mogelijke waarden: 1..255 Standaard: 0 (geen expliciete onderbreking) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Geen onderbreking. Deze eigenschap specificeert de "ononderbreekbare" eigenschap van het objectbox. Wanneer true, kunnen er geen regeleinden binnen de box optreden. Dit kan belangrijk zijn voor operator-emulators die uit meer dan één binaire operator bestaan. Wanneer dit element niet gespecificeerd is, kunnen er onderbrekingen binnen de box optreden. Standaard: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator-emulator. Wanneer true, gedragen de box en de inhoud zich als één enkele operator en erven de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regeleinde en kan worden uitgelijnd met andere operatoren. Operator-emulators worden vaak gebruikt wanneer één of meer glyphs combineren tot een operator, zoals '=='. Standaardwaarde: false |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Stelt een accentteken in (een teken boven dit element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Neemt de opgegeven functie waarbij dit exemplaar als argument en een opgegeven extra argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Neemt de opgegeven functie waarbij dit exemplaar als argument en een opgegeven extra argument wordt gebruikt |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Maak een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Maak een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omwikkelt een wiskundig element met haakjes |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Omwikkelt een wiskundig element met opgegeven tekens, zoals haakjes of andere tekens als kader |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Neemt een functie van een argument waarbij dit exemplaar als functienaam wordt gebruikt |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Neemt een functie van een argument waarbij dit exemplaar als functienaam wordt gebruikt |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Haal kindelementen op |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Plaatst dit element in een groep met behulp van een accolade onderaan |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Plaatst dit element in een groep met een groeperingskarakter, zoals een accolade onderaan of een ander teken |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Neemt het integraal zonder limieten |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Neemt het integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Neemt het integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Neemt het integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Neemt het integraal |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Voegt een wiskundige tekst samen en vormt een wiskundig blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Maakt een N-aire operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Maakt een N-aire operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Stelt een balk boven dit element in |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specificeert de wiskundige wortel van de gegeven graad vanuit het opgegeven argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specificeert de wiskundige wortel van de gegeven graad vanuit het opgegeven argument. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Neemt de ondergrens |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Neemt de ondergrens |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Maakt subscript |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Maakt subscript |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Maakt subscript en superscript aan de linkerkant |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Maakt subscript en superscript aan de linkerkant |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Maakt subscript en superscript aan de rechterkant |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Maakt subscript en superscript aan de rechterkant |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Maakt superscript |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Maakt superscript |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Neemt de bovengrens |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Neemt de bovengrens |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Plaatst dit element in een rand-box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Plaatst dit element in een rand-box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Plaats dit element in een niet-visuele box (logische groepering) die wordt gebruikt om componenten van een vergelijking of andere wiskundige tekst te groeperen. Een verpakt object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, kan dienen als een regeleinde-punt, of kan worden gegroepeerd zodat er geen regeleinden binnen worden toegestaan. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Plaatst in een verticale reeks |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Stelt een balk onder dit element in |

### Voorbeelden

Voorbeeld:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Zie ook

* klasse [MathElementBase](../mathelementbase)
* interface [IMathBox](../imathbox)
* naamruimte [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->