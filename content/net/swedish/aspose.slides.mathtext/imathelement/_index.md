---
title: IMathElement
second_title: Aspose.Sildes för .NET API-referens
description: Basgränssnitt för alla matematiska element: bråk, matematisk text, funktion, uttryck med flera element etc
type: docs
weight: 8210
url: /sv/aspose.slides.mathtext/imathelement/
---
## IMathElement gränssnitt

Basgränssnitt för alla matematiska element: bråk, matematisk text, funktion, uttryck med flera element etc

```csharp
public interface IMathElement
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Ställer in ett accenttecken (ett tecken på toppen av detta element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Tar en specificerad funktion med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Tar en specificerad funktion med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Tar en specificerad funktion med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Tar en specificerad funktion med detta objekt som argument och ett specificerat ytterligare argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Tar en specificerad funktion med detta objekt som argument och ett specificerat ytterligare argument |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Skapar ett bråk med detta täljare och specificerad nämnare |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Skapar ett bråk med detta täljare och specificerad nämnare |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Skapar ett bråk av den specificerade typen med detta täljare och specificerad nämnare |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Skapar ett bråk av den specificerade typen med detta täljare och specificerad nämnare |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Innesluter ett matematiskt element i parentes |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Innesluter detta element i specificerade tecken, såsom parentes eller andra tecken som ram |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Hämtar underordnade element |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Placerar detta element i en grupp med en nedre klammerparentes |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Placerar detta element i en grupp med ett grupperings-tecken, såsom nedre klammerparentes eller annat |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Tar integralen utan gränser |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Tar integralen |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Kombinerar ett matematiskt element och bildar ett matematiskt block |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Kombinerar en matematisk text och bildar ett matematiskt block |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Skapar en N-är operator |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Skapar en N-är operator |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Ställer in en linje på toppen av detta element |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Anger den matematiska roten av given grad från det specificerade argumentet. |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Anger den matematiska roten av given grad från det specificerade argumentet. |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Tar nedre gräns |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Tar nedre gräns |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Skapar nedsänkt |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Skapar nedsänkt |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjt på vänster sida |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Skapar nedsänkt och upphöjt på vänster sida |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjt på höger sida |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Skapar nedsänkt och upphöjt på höger sida |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Skapar upphöjt |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Skapar upphöjt |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Tar övre gräns |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Tar övre gräns |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Placerar detta element i en kantlåda |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Placerar detta element i en kantlåda |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Placerar detta element i en icke-visuell låda (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text. Ett låst objekt kan (till exempel) fungera som en operatoremulator med eller utan en justeringspunkt, fungera som en radbrytningspunkt, eller grupperas så att radbrytningar inte tillåts inom den. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Sätter in en vertikal matris |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Ställer in en linje på botten av detta element |

### Exempel

Exempel:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Se även

* namnrymd [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->