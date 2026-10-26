---
title: MathBlock
second_title: Aspose.Sildes för .NET API-referens
description: Specificerar en instans av matematisk text som finns inom ett MathParagraph och börjar på en egen rad. Alla matematiska zoner inklusive ekvationer, uttryck, matriser av ekvationer eller uttryck och formler representeras av ett math-block.
type: docs
weight: 8590
url: /sv/aspose.slides.mathtext/mathblock/
---
## MathBlock klass

Specificerar en instans av matematisk text som finns inom ett MathParagraph och börjar på en egen rad. Alla matematiska zoner, inklusive ekvationer, uttryck, matriser av ekvationer eller uttryck och formler representeras av ett math-block.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Konstruktörer

| Name | Description |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Initierar en ny instans av MathBlock-klassen. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Skapar ett nytt matematiskt block och placerar angivna element i det |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Skapar ett nytt matematiskt block och placerar angivet element i det |

## Egenskaper

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Hämtar antalet child math-element som faktiskt finns i samlingen. Skrivskyddad Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Returnerar false eftersom samlingen av child-element kan modifieras. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Hämtar eller anger IMathElement på det angivna indexet. |

## Metoder

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ställer in ett accenttecken (ett tecken ovanpå detta element) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Lägger till ett math-element i slutet av samlingen. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Tar angiven funktion med denna instans som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Tar angiven funktion med denna instans som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Tar angiven funktion med denna instans som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Tar angiven funktion med denna instans som argument och ett angivet ytterligare argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Tar angiven funktion med denna instans som argument och ett angivet ytterligare argument |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Tar bort alla element från samlingen. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Avgör om samlingen innehåller ett specifikt värde. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Kopierar till angiven array. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Avgränsar child-element med avgränsningstecken (utan hakparenteser) |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Skapar en bråk med detta täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Skapar en bråk med detta täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Skapar en bråk av angiven typ med detta täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Skapar en bråk av angiven typ med detta täljare och angiven nämnare |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Innesluter ett math-element i parentes |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Innesluter child-element i detta block med angivna tecken såsom parentes eller andra tecken som ram |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Innesluter child-element i detta block med angivna tecken såsom parentes eller andra som ram och avgränsar med ett separator-tecken |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Tar en funktion av ett argument med denna instans som funktionsnamn |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Tar en funktion av ett argument med denna instans som funktionsnamn |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Hämtar child-element |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Placera detta element i en grupp med en botten-klammerparentes |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Placera detta element i en grupp med ett grupperande tecken såsom botten-klammerparentes eller annat |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Avgör indexet för ett specifikt math-element i samlingen. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Infogar ett MathElement i samlingen på det angivna indexet. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Tar integralen utan gränser |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Tar integralen |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Förenar ett matematiskt element med detta matematiska block |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Förenar en matematisk text med detta matematiska block |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Förenar ett annat matematiskt block med detta |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Skapar en N-är operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Skapar en N-är operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Sätter en linje ovanför detta element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specificerar den matematiska roten av given grad från det angivna argumentet. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specificerar den matematiska roten av given grad från det angivna argumentet. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Tar bort elementet på det angivna indexet i samlingen. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Tar nedre gräns |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Tar nedre gräns |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Skapar en nedsänkt term |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Skapar en nedsänkt term |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjd text på vänster sida |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Skapar nedsänkt och upphöjd text på vänster sida |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjd text på höger sida |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Skapar nedsänkt och upphöjd text på höger sida |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Skapar upphöjd text |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Skapar upphöjd text |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Tar övre gräns |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Tar övre gräns |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Placera detta element i en ram-box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Placera detta element i en ram-box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Placera detta element i en icke-visuell ruta (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text. Ett inramat objekt kan (till exempel) fungera som en operator-emulator med eller utan en justeringspunkt, fungera som en radbrytning eller grupperas så att radbrytningar inte tillåts inom. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Placera child-element i en vertikal matris |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Sätter en linje på botten av detta element |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Sparar innehållet i denna [`MathBlock`](../mathblock) som MathML |

### Exempel

Example:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Se även

* klass [MathElementBase](../mathelementbase)
* gränssnitt [IMathBlock](../imathblock)
* namnrymd [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->