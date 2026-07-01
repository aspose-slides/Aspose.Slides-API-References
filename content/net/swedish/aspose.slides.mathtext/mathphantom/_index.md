---
title: MathPhantom
second_title: Aspose.Slides för .NET API-referens
description: Representerar ett fantom-matematikobjekt ltmphantgt som påverkar layouten för dess barn-element utan att nödvändigtvis visa det. Ett fantom kan dölja sitt grunduttryck samtidigt som det bevarar dess bredd, höjd eller djup för att justera formler eller reservera utrymme. Synlighet och geometribeteende styrs av egenskaper som Show, ZeroWid, ZeroAsc, ZeroDesc och Transp.
type: docs
weight: 8900
url: /sv/aspose.slides.mathtext/mathphantom/
---
## MathPhantom klass

Representerar ett fantom-matematikobjekt (<m:phant>) som påverkar layouten för dess barn-element utan att nödvändigtvis visa det. Ett fantom kan dölja sitt grunduttryck samtidigt som det bevarar dess bredd, höjd eller djup för att justera formler eller reservera utrymme. Synlighet och geometribeteende styrs av egenskaper såsom Show, ZeroWid, ZeroAsc, ZeroDesc och Transp.

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## Konstruktorer

| Namn | Beskrivning |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | Skapar en ny instans av [`MathPhantom`](../mathphantom)-klassen med det angivna grundmatematiska elementet. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | Basargument |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | Hämtar eller anger ett värde som indikerar om grundelementet visas. |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | Hämtar eller anger ett värde som indikerar om fantomet är transparent för klassbaserade avståndsregler. |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | Hämtar eller anger ett värde som indikerar om uppstigningen (höjden över baslinjen) för grundelementet ska behandlas som noll. |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | Hämtar eller anger ett värde som indikerar om nedstigningen (djupet under baslinjen) för grundelementet ska behandlas som noll. |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | Hämtar eller anger ett värde som indikerar om bredden på grundelementet ska behandlas som noll. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ställer in ett accenttecken (ett tecken på toppen av detta element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Tar angiven funktion där denna instans används som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Tar angiven funktion där denna instans används som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Tar angiven funktion där denna instans används som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Tar angiven funktion där denna instans används som argument samt ett angivet ytterligare argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Tar angiven funktion där denna instans används som argument samt ett angivet ytterligare argument |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Skapar ett bråk med detta täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Skapar ett bråk med detta täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omsluter ett matematikelement i parenteser |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Omsluter ett matematikelement i specificerade tecken, såsom parenteser eller andra tecken som ram |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Tar en funktion av ett argument där denna instans används som funktionsnamn |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Tar en funktion av ett argument där denna instans används som funktionsnamn |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | Hämtar barn-element |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Placera detta element i en grupp med en nedre klammerparentes |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Placera detta element i en grupp med ett grupperingstecken, såsom nedre klammerparentes eller annat |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Tar integralen utan gränser |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Tar integralen |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Sammanfogar ett matematikelement och bildar ett matematiskt block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Sammanfogar en matematisk text och bildar ett block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Skapar en N-är operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Skapar en N-är operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Sätter ett streck över detta element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Anger den matematiska roten av given grad från det angivna argumentet |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Anger den matematiska roten av given grad från det angivna argumentet |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Tar nedre gräns |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Tar nedre gräns |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Skapar ett nedsänkt tecken |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Skapar ett nedsänkt tecken |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Skapar både subscript och superscript till vänster |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Skapar både subscript och superscript till vänster |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Skapar både subscript och superscript till höger |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Skapar både subscript och superscript till höger |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Skapar superscript |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Skapar superscript |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Tar övre gräns |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Tar övre gräns |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Placera detta element i en kant-ruta |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Placera detta element i en kant-ruta |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Placera detta element i en icke-visuell ruta (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan matematisk text. Ett inramat objekt kan (till exempel) fungera som en operator-emulator med eller utan en justeringspunkt, fungera som en radbrytpunkt eller grupperas så att radbrytningar inte tillåts inom den. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Placera i en vertikal matris |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Sätter ett streck under detta element |

### Exempel

```csharp
[C#]
IMMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // Dölj innehållet
phantom.ZeroWidth = false;     // Behåll bredden
```

### Se även

* klass [MathElementBase](../mathelementbase)
* gränssnitt [IMathPhantom](../imathphantom)
* namnrymd [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->