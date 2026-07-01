---
title: MathBlock
second_title: Aspose.Sildes för .NET API-referens
description: Specificerar en instans av matematisk text som finns i ett MathParagraph och börjar på en egen rad. Alla matematiska zoner, inklusive ekvationer, uttryck, matriser av ekvationer eller uttryck och formler representeras av MathBlock.
type: docs
weight: 8570
url: /sv/aspose.slides.mathtext/mathblock/
---
## MathBlock klass

Specificerar en instans av matematisk text som finns i ett MathParagraph och börjar på en egen rad. Alla matematiska zoner, inklusive ekvationer, uttryck, matriser av ekvationer eller uttryck och formler representeras av ett matematiskt block.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Initierar en ny instans av MathBlock-klassen. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Skapar ett nytt matematiskt block och placerar de angivna elementen i det. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Skapar ett nytt matematiskt block och placerar det angivna elementet i det. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Hämtar antalet underordnade matematiska element som faktiskt finns i samlingen. Skrivskyddad Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Returnerar false eftersom samlingen av underordnade element kan modifieras. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Hämtar eller anger IMathElement på det angivna indexet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ställer in ett accenttecken (ett tecken ovanför detta element). |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Lägger till ett matematiskt element i slutet av samlingen. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Använder den angivna funktionen med detta objekt som argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Använder den angivna funktionen med detta objekt som argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Använder den angivna funktionen med detta objekt som argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Använder den angivna funktionen med detta objekt som argument samt ett angivet ytterligare argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Använder den angivna funktionen med detta objekt som argument samt ett angivet ytterligare argument. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Tar bort alla element från samlingen. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Avgör om samlingen innehåller ett specifikt värde. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Kopierar till den angivna arrayen. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Avgränsar underordnade element med ett avgränsningstecken (utan hakparenteser). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Skapar ett bråk med detta täljare och angiven nämnare. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Skapar ett bråk med detta täljare och angiven nämnare. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omger ett matematiskt element med parenteser. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Omger underordnade element i detta block med angivna tecken, såsom parenteser eller andra tecken som ram. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Omger underordnade element i detta block med angivna tecken, såsom parenteser eller andra, som ram och avgränsar med ett avgränsningstecken. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Använder en funktion för ett argument med detta objekt som funktionsnamn. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Använder en funktion för ett argument med detta objekt som funktionsnamn. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Hämtar underordnade element. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Placera detta element i en grupp med en nedre klammerparentes. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Placera detta element i en grupp med ett grupperingstecken, såsom en nedre klammerparentes eller annat. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Bestämmer indexet för ett specifikt matematiskt element i samlingen. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Infogar ett MathElement i samlingen på det angivna indexet. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Beräknar integralen utan gränser. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Beräknar integralen. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Beräknar integralen. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Beräknar integralen. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Beräknar integralen. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Förenar ett matematiskt element med detta matematiska block. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Förenar matematisk text med detta matematiska block. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Förenar ett annat matematiskt block med detta. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Skapar en N-är operator. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Skapar en N-är operator. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Sätter ett streck ovanpå detta element. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Tar bort elementet på det angivna indexet i samlingen. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Tar den nedre gränsen. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Tar den nedre gränsen. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Skapar nedsänkt index. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Skapar nedsänkt index. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjt index på vänster sida. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Skapar nedsänkt och upphöjt index på vänster sida. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjt index på höger sida. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Skapar nedsänkt och upphöjt index på höger sida. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Skapar upphöjt index. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Skapar upphöjt index. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Tar den övre gränsen. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Tar den övre gränsen. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Placera detta element i en ramruta. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Placera detta element i en ramruta. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Placera detta element i en icke-visuell låda (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text. Ett inramat objekt kan (till exempel) fungera som en operatoremulator med eller utan en justeringspunkt, fungera som en radbrytningspunkt eller grupperas så att radbrytningar inte tillåts inom den. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Placera underordnade element i en vertikal matris. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Sätter ett streck under detta element. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Sparar innehållet i detta [`MathBlock`](../mathblock) som MathML |

### Exempel

Exempel:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Se också

* klass [MathElementBase](../mathelementbase)
* gränssnitt [IMathBlock](../imathblock)
* namnområde [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->