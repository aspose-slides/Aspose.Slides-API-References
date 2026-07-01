---
title: MathFraction
second_title: Aspose.Sildes för .NET API-referens
description: Specificerar bråkobjektet bestående av en täljare och en nämnare separerade av ett bråkstreck. Bråkstrecket kan vara horisontellt eller diagonalt beroende på bråkegenskaperna. Bråkobjektet används också för att representera stapelfunktionen som placerar ett element ovanför ett annat utan bråkstreck.
type: docs
weight: 8670
url: /sv/aspose.slides.mathtext/mathfraction/
---
## MathFraction klass

Specificerar bråkobjektet, bestående av en täljare och en nämnare separerade av en bråkstreck. Bråkstrecket kan vara horisontellt eller diagonalt, beroende på bråkegenskaperna. Bråkobjektet används också för att representera staplingsfunktionen, som placerar ett element ovanför ett annat, utan bråkstreck.

```csharp
public sealed class MathFraction : MathElementBase, IMathFraction
```

## Konstruktorer

| Namn | Beskrivning |
| --- | --- |
| [MathFraction](mathfraction#constructor)(IMathElement, IMathElement) | Initierar en MathFraction av typen 'Bar' med den angivna täljaren och nämnaren |
| [MathFraction](mathfraction#constructor_1)(IMathElement, IMathElement, MathFractionTypes) | Initierar MathFraction med den angivna täljaren, nämnaren och typen |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Denominator](../../aspose.slides.mathtext/mathfraction/denominator) { get; } | Nämnare |
| [FractionType](../../aspose.slides.mathtext/mathfraction/fractiontype) { get; set; } | Bråktyp Standard: Bar |
| [Numerator](../../aspose.slides.mathtext/mathfraction/numerator) { get; } | Täljare |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ställer in ett accenttecken (ett tecken ovanpå detta element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Tar angiven funktion med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Tar angiven funktion med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Tar angiven funktion med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Tar angiven funktion med detta objekt som argument och angivet ytterligare argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Tar angiven funktion med detta objekt som argument och angivet ytterligare argument |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Skapar ett bråk med denna täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Skapar ett bråk med denna täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Skapar ett bråk av angiven typ med denna täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Skapar ett bråk av angiven typ med denna täljare och angiven nämnare |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omger ett matematiskt element med parenteser |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Omger ett matematiskt element med angivna tecken, såsom parentes eller andra inramande tecken |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [GetChildren](../../aspose.slides.mathtext/mathfraction/getchildren)() | Hämtar underordnade element |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Placerar detta element i en grupp med en nedre hakparentes |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Placerar detta element i en grupp med ett inramningstecken, såsom nedre hakparentes eller annat |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Tar integralen utan gränser |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Tar integralen |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Förena ett matematiskt element och bildar ett matematiskt block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Förena en matematisk text och bildar ett matematiskt block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Skapar en N-är operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Skapar en N-är operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Sätter ett streck ovanpå detta element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Anger den matematiska roten av given grad från angivet argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Anger den matematiska roten av given grad från angivet argument. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Tar nedre gräns |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Tar nedre gräns |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Skapar index nedanför |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Skapar index nedanför |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Skapar index nedanför och exponent ovanför till vänster |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Skapar index nedanför och exponent ovanför till vänster |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Skapar index nedanför och exponent ovanför till höger |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Skapar index nedanför och exponent ovanför till höger |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Skapar exponent ovanför |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Skapar exponent ovanför |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Tar övre gräns |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Tar övre gräns |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Placerar detta element i en kant-ruta |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Placerar detta element i en kant-ruta |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Placerar detta element i en icke-visuell ruta (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan matematisk text. En ramad objekt kan (till exempel) fungera som en operatoremulator med eller utan justeringspunkt, fungera som en radbrytpunkt, eller grupperas så att radbrytningar inte tillåts inom den. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Sätter i en vertikal matris |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Sätter ett streck under detta element |

### Exempel

Exempel:

```csharp
[C#]
MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```

### Se även

* klass [MathElementBase](../mathelementbase)
* gränssnitt [IMathFraction](../imathfraction)
* namnrymd [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->