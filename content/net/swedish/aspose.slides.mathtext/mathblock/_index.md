---
title: MathBlock
second_title: Aspose.Sildes för .NET API-referens
description: Specificerar en instans av matematisk text som finns i ett MathParagraph och börjar på en egen rad. Alla matematiska områden, inklusive ekvationer, uttryck, arrayer av ekvationer eller uttryck och formler, representeras av ett math block.
type: docs
weight: 8610
url: /sv/aspose.slides.mathtext/mathblock/
---
## MathBlock klass

Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line. All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Konstruktorer

| Namn | Beskrivning |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Initierar en ny instans av MathBlock klass. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Skapar ett nytt matematiskt block och placerar angivna element i det. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Skapar ett nytt matematiskt block och placerar angivet element i det. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Hämtar antalet barn-mathelement som faktiskt finns i samlingen. Skrivskyddad Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Returnerar false eftersom samlingen av barn-element kan modifieras. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Hämtar eller anger IMathElement på angivet index. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Sätter ett accenttecken (ett tecken ovanpå detta element) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Lägger till ett mathelement i slutet av samlingen. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Tar angiven funktion med denna instans som argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Tar angiven funktion med denna instans som argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Tar angiven funktion med denna instans som argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Tar angiven funktion med denna instans som argument och specificerat ytterligare argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Tar angiven funktion med denna instans som argument och specificerat ytterligare argument. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Tar bort alla element från samlingen. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Bestämmer om samlingen innehåller ett specifikt värde. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Kopierar till angiven array. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Avgränsar barn-element med avgränsartecken (utan hakparenteser). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Skapar en bråkdel med detta täljare och angiven nämnare. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Skapar en bråkdel med detta täljare och angiven nämnare. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Skapar en bråkdel av angiven typ med detta täljare och angiven nämnare. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Skapar en bråkdel av angiven typ med detta täljare och angiven nämnare. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Innesluter ett mathelement i parenteser. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Innesluter barn-element i detta block med angivna tecken såsom parenteser eller andra tecken som ram. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Innesluter barn-element i detta block med angivna tecken såsom parenteser eller andra som ram och avgränsar med ett avgränsartecken. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Tar en funktion av ett argument med denna instans som funktionsnamn. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Tar en funktion av ett argument med denna instans som funktionsnamn. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Hämtar barn-element. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Placera detta element i en grupp med en nedre klammerparentes. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Placera detta element i en grupp med ett grupptecken såsom nedre klammerparentes eller annat. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Bestämmer indexet för ett specifikt mathelement i samlingen. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Infogar ett MathElement i samlingen på angivet index. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Tar integralen utan gränser. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Tar integralen. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Tar integralen. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Tar integralen. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Tar integralen. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Kombinerar ett matematiskt element med detta matematiska block. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Kombinerar en matematisk text med detta matematiska block. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Kombinerar ett annat matematiskt block med detta. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Skapar en N-är operator. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Skapar en N-är operator. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Sätter ett streck ovanpå detta element. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Tar bort elementet på angivet index i samlingen. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Tar lägre gräns. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Tar lägre gräns. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Skapar nedsänkt index. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Skapar nedsänkt index. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjt index till vänster. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Skapar nedsänkt och upphöjt index till vänster. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjt index till höger. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Skapar nedsänkt och upphöjt index till höger. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Skapar upphöjt index. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Skapar upphöjt index. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Tar övre gräns. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Tar övre gräns. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Placera detta element i en kantlåda. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Placera detta element i en kantlåda. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Placera detta element i en icke-visuell låda (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan matematisk text. Ett låst objekt kan (till exempel) fungera som en operator-emulator med eller utan en justeringspunkt, fungera som en radbrytningspunkt, eller grupperas så att radbrytningar inte tillåts inom den. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Placera barn-element i en vertikal matris. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Sätter ett streck under detta element. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Sparar innehållet av denna [`MathBlock`](../mathblock) som MathML. |

### Exempel

Exempel:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Se även

* klass [MathElementBase](../mathelementbase)
* gränssnitt [IMathBlock](../imathblock)
* namnrymd [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->