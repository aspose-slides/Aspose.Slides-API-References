---
title: MathRightSubSuperscriptElement
second_title: Aspose.Sildes för .NET API-referens
description: Anger Sub-Superscript-objektet som består av en bas samt en nedsänkt och en upphöjd skrivning placerad till höger om basen.
type: docs
weight: 8940
url: /sv/aspose.slides.mathtext/mathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElement klass

Anger Sub-Superscript-objektet, som består av en bas samt en nedsänkt och en upphöjd skrivning placerad till höger om basen.

```csharp
public sealed class MathRightSubSuperscriptElement : BaseScript, IMathRightSubSuperscriptElement
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MathRightSubSuperscriptElement](mathrightsubsuperscriptelement)(IMathElement, IMathElement, IMathElement) | Skapar en ny instans av MathRightSubSuperscriptElement klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlignScripts](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/alignscripts) { get; set; } | Anger justeringen av nedsänkt/upphöjd. När true är nedsänkt och upphöjd horisontellt justerade mot varandra. När false är de anpassade till basens form. Standardvärdet är false. |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | Basargument |
| [Subscript](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript) { get; } | Nedsänkt argument |
| [Superscript](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/superscript) { get; } | Upphöjd argument |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ställer in ett accenttecken (ett tecken på toppen av detta element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Tar angiven funktion med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Tar angiven funktion med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Tar angiven funktion med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Tar angiven funktion med detta objekt som argument och ett angivet ytterligare argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Tar angiven funktion med detta objekt som argument och ett angivet ytterligare argument |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Skapar ett bråk med detta täljare och angivet nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Skapar ett bråk med detta täljare och angivet nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Skapar ett bråk av den angivna typen med detta täljare och angivet nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Skapar ett bråk av den angivna typen med detta täljare och angivet nämnare |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omsluter ett matematiskt element i parenteser |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Omsluter ett matematiskt element i angivna tecken, såsom parenteser eller andra tecken som ram |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Tar en funktion av ett argument där detta objekt används som funktionsnamn |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Tar en funktion av ett argument där detta objekt används som funktionsnamn |
| [GetChildren](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/getchildren)() | Hämta underordnade element |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Placera detta element i en grupp med en nedersta klammerparentes |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Placera detta element i en grupp med ett grupperingstecken, såsom en nedersta klammerparentes eller ett annat tecken |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Tar integralen utan gränser |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Tar integralen |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Sammanfogar ett matematiskt element och bildar ett matematiskt block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Sammanfogar en matematisk text och bildar ett matematiskt block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Skapar en N-ary-operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Skapar en N-ary-operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Ställer in ett streck på toppen av detta element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Anger den matematiska roten av given grad från det specificerade argumentet. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Anger den matematiska roten av given grad från det specificerade argumentet. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Tar lägre gräns |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Tar lägre gräns |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Skapar nedsänkt |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Skapar nedsänkt |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjd på vänster sida |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Skapar nedsänkt och upphöjd på vänster sida |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjd på höger sida |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Skapar nedsänkt och upphöjd på höger sida |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Skapar upphöjd |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Skapar upphöjd |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Tar övre gräns |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Tar övre gräns |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Placera detta element i en kantlåda |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Placera detta element i en kantlåda |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Placera detta element i en icke-visuell ruta (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan matematisk text. Ett inramat objekt kan (till exempel) fungera som en operatoremulator med eller utan en justeringspunkt, fungera som en radbrytpunkt, eller grupperas så att radbrytningar inte tillåts inom den. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Sätter in en vertikal matris |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Ställer in ett streck på botten av detta element |

### Exempel

Exempel:

```csharp
[C#]
MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
```

### Se också

* klass [BaseScript](../basescript)
* gränssnitt [IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement)
* namnrymd [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->