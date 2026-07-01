---
title: MathLeftSubSuperscriptElement
second_title: Aspose.Sildes för .NET API-referens
description: Specificerar Sub-Superskript-objektet som består av en bas och ett nedsänkt och ett upphöjt skript placerade till vänster om basen.
type: docs
weight: 8790
url: /sv/aspose.slides.mathtext/mathleftsubsuperscriptelement/
---
## MathLeftSubSuperscriptElement klass

Specificerar Sub-Superskript-objektet, som består av en bas samt en nedsänkt och en upphöjd skript placerade till vänster om basen.

```csharp
public sealed class MathLeftSubSuperscriptElement : BaseScript, IMathLeftSubSuperscriptElement
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MathLeftSubSuperscriptElement](mathleftsubsuperscriptelement)(IMathElement, IMathElement, IMathElement) | Initierar en ny instans av MathLeftSubSuperscriptElement klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | Basargument |
| [Subscript](../../aspose.slides.mathtext/mathleftsubsuperscriptelement/subscript) { get; } | Nedsänkt skript |
| [Superscript](../../aspose.slides.mathtext/mathleftsubsuperscriptelement/superscript) { get; } | Upphöjt skript |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ställer in ett accenttecken (ett tecken ovanpå detta element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Tar angiven funktion där denna instans används som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Tar angiven funktion där denna instans används som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Tar angiven funktion där denna instans används som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Tar angiven funktion där denna instans används som argument och angivet ytterligare argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Tar angiven funktion där denna instans används som argument och angivet ytterligare argument |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Skapar en bråk med detta täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Skapar en bråk med detta täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Skapar en bråk av den angivna typen med detta täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Skapar en bråk av den angivna typen med detta täljare och angiven nämnare |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omger ett matematiskt element med parenteser |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Omger ett matematiskt element med angivna tecken såsom parenteser eller andra tecken som ram |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Tar en funktion av ett argument där denna instans används som funktionsnamn |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Tar en funktion av ett argument där denna instans används som funktionsnamn |
| [GetChildren](../../aspose.slides.mathtext/mathleftsubsuperscriptelement/getchildren)() | Hämtar underordnade element |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Placera detta element i en grupp med en bottenklammer |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Placera detta element i en grupp med ett grupperingstecken såsom bottenklammer eller annat |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Tar integralen utan gränser |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Tar integralen |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Sammanfogar ett matematiskt element och bildar ett matematiskt block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Sammanfogar en matematisk text och bildar ett matematiskt block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Skapar en N-är operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Skapar en N-är operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Sätter ett streck på toppen av detta element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Tar lägre gräns |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Tar lägre gräns |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Skapar nedsänkt skript |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Skapar nedsänkt skript |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjd skript till vänster |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Skapar nedsänkt och upphöjd skript till vänster |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjd skript till höger |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Skapar nedsänkt och upphöjd skript till höger |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Skapar upphöjd skript |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Skapar upphöjd skript |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Tar övre gräns |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Tar övre gräns |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Placera detta element i en kant-ruta |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Placera detta element i en kant-ruta |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Placera detta element i en icke-visuell ruta (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan matematisk text. En inramad objekt kan (till exempel) fungera som en operator-emulator med eller utan en justeringspunkt, fungera som en radbrytning eller grupperas så att radbrytningar inte tillåts inom den. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Sätter in i en vertikal matris |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Sätter ett streck på botten av detta element |

### Exempel

Exempel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
```

### Se också

* klass [BaseScript](../basescript)
* gränssnitt [IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement)
* namnrymd [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* montering [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->