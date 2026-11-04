---
title: MathPhantom
second_title: Aspose.Sildes för .NET API-referens
description: Representerar ett fantom-matematiktobjekt ltmphantgt som påverkar layouten för dess underordnade element utan att nödvändigtvis visas. Ett fantom kan dölja sitt basuttryck samtidigt som det bevarar dess bredd, höjd eller djup för att justera formler eller reservera utrymme. Synlighet och geometribeteende styrs av egenskaper såsom Show, ZeroWid, ZeroAsc, ZeroDesc och Transp.
type: docs
weight: 8940
url: /sv/aspose.slides.mathtext/mathphantom/
---
## MathPhantom klass

Representerar ett fantom-matematikobjekt (<m:phant>) som påverkar layouten för dess underordnade element utan att nödvändigtvis visas. Ett fantom kan dölja sitt basuttryck medan det bevarar dess bredd, höjd eller djup för att justera formler eller reservera utrymme. Synlighet och geometribeteende styrs av egenskaper såsom Show, ZeroWid, ZeroAsc, ZeroDesc och Transp.

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## Konstruktorer

| Name | Description |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | Initierar en ny instans av [`MathPhantom`](../mathphantom) klass med det angivna bas-matte-elementet. |

## Egenskaper

| Name | Description |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | Basargument |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | Hämtar eller anger ett värde som visar om bas-elementet visas. |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | Hämtar eller anger ett värde som visar om fantomet är transparent för klassbaserade avståndsregler. |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | Hämtar eller anger ett värde som visar om höjden (stigning över baslinjen) för bas-elementet ska behandlas som noll. |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | Hämtar eller anger ett värde som visar om nedstigningen (djup under baslinjen) för bas-elementet ska behandlas som noll. |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | Hämtar eller anger ett värde som visar om bredden på bas-elementet ska behandlas som noll. |

## Metoder

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ställer in ett accenteringstecken (ett tecken ovanpå detta element). |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Tar den angivna funktionen med detta objekt som argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Tar den angivna funktionen med detta objekt som argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Tar den angivna funktionen med detta objekt som argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Tar den angivna funktionen med detta objekt som argument och angivet extra argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Tar den angivna funktionen med detta objekt som argument och angivet extra argument. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Skapar ett bråk med detta täljare och angivet nämnare. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Skapar ett bråk med detta täljare och angivet nämnare. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Skapar ett bråk av angiven typ med detta täljare och angivet nämnare. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Skapar ett bråk av angiven typ med detta täljare och angivet nämnare. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Innesluter ett matematiskt element i parenteser. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Innesluter ett matematiskt element i angivna tecken, såsom parenteser eller andra tecken som ram. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Tar en funktion med ett argument där detta objekt används som funktionsnamn. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Tar en funktion med ett argument där detta objekt används som funktionsnamn. |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | Hämtar underordnade element. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Placera detta element i en grupp med en nedre klammerparentes. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Placera detta element i en grupp med ett grupperingstecken, såsom en nedre klammerparentes eller annat. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Tar integralen utan gränser. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Tar integralen. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Tar integralen. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Tar integralen. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Tar integralen. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Sammanfogar ett matematiskt element och bildar ett matematiskt block. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Sammanfogar en matematisk text och bildar ett matematiskt block. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Skapar en N-är operator. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Skapar en N-är operator. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Ställer in en linje högst upp på detta element. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Tar lägre gräns. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Tar lägre gräns. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Skapar en nedsänkt index. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Skapar en nedsänkt index. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Skapar både nedsänkt och upphöjd index på vänster sida. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Skapar både nedsänkt och upphöjd index på vänster sida. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Skapar både nedsänkt och upphöjd index på höger sida. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Skapar både nedsänkt och upphöjd index på höger sida. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Skapar upphöjd index. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Skapar upphöjd index. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Tar övre gräns. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Tar övre gräns. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Placera detta element i en kant-ruta. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Placera detta element i en kant-ruta. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Placera detta element i en icke-visuell ruta (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text. Ett inramat objekt kan (till exempel) fungera som en operator-emulator med eller utan en justeringspunkt, fungera som en rad-brytpunkt eller grupperas så att radbrytningar inte tillåts inom. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Sätter in i en vertikal matris. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Ställer in en linje längst ner på detta element. |

### Exempel

Example:

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
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->