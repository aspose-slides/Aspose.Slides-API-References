---
title: MathBox
second_title: Aspose.Slides för .NET API-referens
description: Anger den logiska förpackningen av ett matematiskt element. Till exempel kan ett inneslutet objekt fungera som en operator-emulator med eller utan en justeringspunkt, fungera som en radbrytningspunkt eller grupperas så att radbrytningar inte tillåts inom det. Till exempel bör operatorn boxas för att förhindra radbrytningar.
type: docs
weight: 8610
url: /sv/aspose.slides.mathtext/mathbox/
---
## MathBox-klass

Anger den logiska gruppering (paketering) av ett matematiskt element. Till exempel kan ett inneslutet objekt fungera som en operator-emulator med eller utan en justeringspunkt, fungera som en radbrytning, eller grupperas så att radbrytningar inte tillåts inom det. Till exempel bör operatorn "==" inneslutas för att förhindra radbrytningar.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Konstruktorer

| Namn | Beskrivning |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Initierar MathBox med det angivna elementet som argument |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | När true, fungerar denna operator-emulator som en justeringspunkt; det vill säga, utsedda justeringspunkter i andra ekvationer kan justeras med den. Standard: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Basargument |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Differential När true agerar boxen som en differential (t.ex. 𝑑𝑥 i en integrand) och får lämplig horisontell avstånd för den matematiska differentialen. Standard: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Explicit brytning anger om det finns en radbrytning i början av Box-objektet, så att raden bryts vid start av box-objektet. Anger numret på operatorn på föregående rad i matematisk text som ska användas som justeringspunkt för den aktuella raden i matematisk text möjliga värden: 1..255 Standard: 0 (ingen explicit brytning) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Ingen brytning Denna egenskap anger den "unbreakable" egenskapen på objektboxen. När true kan inga radbrytningar förekomma inom boxen. Detta kan vara viktigt för operator-emulatorer som består av mer än en binär operator. När detta element inte är angivet kan brytningar förekomma i boxen. Standard: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator-emulator. När true beter sig boxen och dess innehåll som en enda operator och ärver egenskaperna hos en operator. Detta innebär till exempel att tecknet kan fungera som en punkt för en radbrytning och kan justeras mot andra operatorer. Operator-emulatorer används ofta när ett eller flera tecken kombineras för att bilda en operator, såsom '=='. Standardvärde: false |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ställer in en accent (ett tecken ovanför detta element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Tar den angivna funktionen med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Tar den angivna funktionen med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Tar den angivna funktionen med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Tar angiven funktion med detta objekt som argument och angivet ytterligare argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Tar angiven funktion med detta objekt som argument och angivet ytterligare argument |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Skapar ett bråk med detta täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Skapar ett bråk med detta täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omsluter ett matematikelement i parentes |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Omsluter ett matematikelement i specifika tecken såsom parentes eller andra tecken som ram |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Hämtar underordnade element |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Placera detta element i en grupp med en nedre klammerparentes |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Placera detta element i en grupp med ett grupperingstecken såsom en nedre klammerparentes eller annat |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Tar integralen utan gränser |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Tar integralen |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Fogar ihop ett matematikelement och bildar ett matematiskt block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Fogar ihop en matematisk text och bildar ett matematiskt block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Skapar en N-är operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Skapar en N-är operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Sätter ett streck över detta element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Tar nedre gräns |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Tar nedre gräns |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Skapar nedsänkt |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Skapar nedsänkt |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjt på vänster sida |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Skapar nedsänkt och upphöjt på vänster sida |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjt på höger sida |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Skapar nedsänkt och upphöjt på höger sida |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Skapar upphöjt |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Skapar upphöjt |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Tar övre gräns |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Tar övre gräns |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Placera detta element i en kantbox |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Placera detta element i en kantbox |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Placera detta element i en icke-visuell box (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan matematisk text. Ett inneslutet objekt kan (till exempel) fungera som en operator-emulator med eller utan en justeringspunkt, fungera som en radbrytning, eller grupperas så att radbrytningar inte tillåts inom den. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Sätter in en vertikal matris |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Sätter ett streck under detta element |

### Exempel

Exempel:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Se även

* klass [MathElementBase](../mathelementbase)
* gränssnitt [IMathBox](../imathbox)
* namnrymd [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->