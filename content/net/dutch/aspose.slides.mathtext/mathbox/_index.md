---
title: MathBox
second_title: Aspose.Sildes voor .NET API-referentie
description: Specificeert de logische verpakkingsbox van een wiskundig element. Bijvoorbeeld kan een verpakt object fungeren als een operator-emulator met of zonder een uitlijningspunt, dienen als een regeleinde-punt, of gegroepeerd worden zodat er geen regeleinden binnen toegestaan zijn. Bijvoorbeeld moet de operator worden verpakt om regeleinden te voorkomen.
type: docs
weight: 8630
url: /nl/aspose.slides.mathtext/mathbox/
---
## MathBox klasse

Specificeert de logische verpakking (verpakking) van een wiskundig element. Bijvoorbeeld, een verpakt object kan dienen als een operator-emulator met of zonder een uitlijningspunt, dienen als een regeleinde-punt, of gegroepeerd worden zodat geen regeleinden binnen voorkomen. Bijvoorbeeld, de "==" operator moet verpakt worden om regeleinden te voorkomen.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Constructoren

| Naam | Beschrijving |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Initialiseert MathBox met het opgegeven element als argument |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Wanneer true, dient deze operator-emulator als een uitlijningspunt; dat wil zeggen, aangewezen uitlijningspunten in andere vergelijkingen kunnen ermee worden uitgelijnd. Standaard: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Basisargument |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Differentiëel: Wanneer true, functioneert de box als een differentiaal (bijv. 𝑑𝑥 in een integrand), en krijgt de juiste horizontale spatiëring voor het wiskundig differentiaal. Standaard: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box-object, zodat de regel wordt afgebroken aan het begin van het box-object. Geeft het aantal van de operator op de vorige regel van wiskundige tekst dat gebruikt moet worden als uitlijningspunt voor de huidige regel van wiskundige tekst. Mogelijke waarden: 1..255 Standaard: 0 (geen expliciete onderbreking) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Geen onderbreking: Deze eigenschap specificeert de “ononderbreekbare” eigenschap van het objectbox. Wanneer true, kunnen er geen regeleinden optreden binnen de box. Dit kan belangrijk zijn voor operator-emulators die uit meer dan één binaire operator bestaan. Wanneer dit element niet gespecificeerd is, kunnen er onderbrekingen binnen de box optreden. Standaard: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator-emulator. Wanneer true, gedragen de box en de inhoud als één enkele operator en erven de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regeleinde en kan worden uitgelijnd met andere operators. Operator-emulators worden vaak gebruikt wanneer één of meer tekens combineren tot een operator, zoals '=='. Standaardwaarde: false |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Stelt een accentteken in (een teken boven dit element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt en een gespecificeerd extra argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt en een gespecificeerd extra argument |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Maakt een breuk met deze teller en een gespecificeerde noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Maakt een breuk met deze teller en een gespecificeerde noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Maakt een breuk van het opgegeven type met deze teller en een gespecificeerde noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Maakt een breuk van het opgegeven type met deze teller en een gespecificeerde noemer |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omvat een wiskundig element in haakjes |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Omvat een wiskundig element in opgegeven tekens, zoals haakjes of andere tekens als omlijsting |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Haalt onderliggende elementen op |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Plaatst dit element in een groep met behulp van een onderste accolade |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Plaatst dit element in een groep met behulp van een groeperingsteken, zoals een onderste accolade of een ander teken |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Neemt het integraal zonder limieten |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Neemt het integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Neemt het integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Neemt het integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Neemt het integraal |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Voegt wiskundige tekst samen en vormt een wiskundig blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Creëert een N-aire operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Creëert een N-aire operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Stelt een balk in boven dit element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specificeert de wiskundige wortel van de opgegeven graad uit het gespecificeerde argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specificeert de wiskundige wortel van de opgegeven graad uit het gespecificeerde argument. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Neemt onderlimiet |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Neemt onderlimiet |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Maakt subscript |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Maakt subscript |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Maakt subscript en superscript aan de linkerkant |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Maakt subscript en superscript aan de linkerkant |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Maakt subscript en superscript aan de rechterkant |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Maakt subscript en superscript aan de rechterkant |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Maakt superscript |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Maakt superscript |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Neemt bovenlimiet |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Neemt bovenlimiet |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Plaatst dit element in een randvak |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Plaatst dit element in een randvak |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Plaatst dit element in een niet-visuele box (logische groepering) die wordt gebruikt om componenten van een vergelijking of andere instantie van wiskundige tekst te groeperen. Een verpakt object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, dienen als een regeleinde-punt, of gegroepeerd worden zodat geen regeleinden binnen voorkomen. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Plaatst in een verticale array |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Stelt een balk in onder dit element |

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