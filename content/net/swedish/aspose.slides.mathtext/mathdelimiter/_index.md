---
title: MathDelimiter
second_title: Aspose.Slides för .NET API-referens
description: Specificerar avgränsarobjektet bestående av öppnings- och stängningstecken såsom parenteser, klammerparenteser, hakparenteser och vertikala streck samt ett eller flera matematiska element inuti, separerade av ett angivet tecken. Exempel 2 2x7C2
type: docs
weight: 8630
url: /sv/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter class

Specificerar avgränsarobjektet, bestående av öppnings- och stängningstecken (såsom parenteser, klammerparenteser, hakparenteser och vertikala streck), samt ett eller flera matematiska element inuti, separerade av ett angivet tecken. Exempel: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## Constructors

| Namn | Beskrivning |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | Initialiserar MathDelimiter med det specificerade elementet som enda basargument |

## Properties

| Namn | Beskrivning |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | Ett eller flera matematiska element separerade av avgränsningstecken |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Delimitrarens inledande tecken anger det inledande, eller öppnande, avgränsningstecknet. Matematiska avgränsare är omslutande tecken såsom parenteser, hakparenteser och klammerparenteser. Standardvärdet: '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | Anger formen på avgränsarna i avgränsarobjektet. När den är MathDelimiterShape.Centered är avgränsarna centrerade kring den matematiska axeln i den matematiska texten och anpassas för att passa hela höjden på deras innehåll. När den är MathDelimiterShape.Match ändras deras höjd och form så att de exakt matchar innehållet. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Delimitrarens avslutande tecken anger det avslutande, eller stängande, avgränsningstecknet. Matematiska avgränsare är omslutande tecken såsom parenteser, hakparenteser och klammerparenteser. Standardvärdet: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | Anger tillväxten för BeginningCharacter, SeparatorCharacter och EndingCharacter. När true växer avgränsarna vertikalt för att matcha operandens höjd. Standardvärdet är true. |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Delimitrarens separator-tecken anger tecknet som separerar argument i avgränsarobjektet. Standardvärdet: '&#x7C;'. |

## Methods

| Namn | Beskrivning |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ställer in ett accenttecken (ett tecken ovanpå detta element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Använder den specificerade funktionen med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Använder den specificerade funktionen med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Använder den specificerade funktionen med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Använder den specificerade funktionen med detta objekt som argument och det angivna ytterligare argumentet |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Använder den specificerade funktionen med detta objekt som argument och det angivna ytterligare argumentet |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | Avgränsar argument med det angivna avgränsningstecknet |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Skapar en bråkdel med detta täljare och den specificerade nämnaren |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Skapar en bråkdel med detta täljare och den specificerade nämnaren |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Skapar en bråkdel av den specificerade typen med detta täljare och den specificerade nämnaren |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Skapar en bråkdel av den specificerade typen med detta täljare och den specificerade nämnaren |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omsluter ett matematiskt element i parentes |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | Omsluter ett matematiskt element i angivna tecken, såsom parentes eller andra ramtecken |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Tar en funktion med ett argument med detta objekt som funktionsnamn |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Tar en funktion med ett argument med detta objekt som funktionsnamn |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | Hämtar underordnade element |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Placera detta element i en grupp med en bottenklammerparentes |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Placera detta element i en grupp med ett grupperingstecken såsom bottenklammerparentes eller annat |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Tar integral utan gränser |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Tar integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Tar integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Tar integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Tar integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Förena ett matematiskt element och bilda ett matematiskt block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Förena en matematisk text och bilda ett matematiskt block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Skapar en N-ary-operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Skapar en N-ary-operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Sätter ett streck över detta element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Anger den matematiska roten av given grad från det specificerade argumentet. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Anger den matematiska roten av given grad från det specificerade argumentet. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Tar nerre gräns |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Tar nerre gräns |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Skapar nedsänkt index |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Skapar nedsänkt index |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjt index på vänster sida |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Skapar nedsänkt och upphöjt index på vänster sida |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjt index på högra sidan |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Skapar nedsänkt och upphöjt index på högra sidan |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Skapar upphöjt index |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Skapar upphöjt index |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Tar övre gräns |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Tar övre gräns |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Placera detta element i en kant-ruta |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Placera detta element i en kant-ruta |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Placera detta element i en icke-visuell ruta (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan matematisk text. En inramad objekt kan t.ex. fungera som en operator-emulator med eller utan justeringspunkt, fungera som ett radbrytningsställe, eller grupperas så att radbrytningar inte tillåts inom. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Sätter in i en vertikal matris |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Sätter ett streck under detta element |

### Exempel

Exempel:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### Se också

* klass [MathElementBase](../mathelementbase)
* gränssnitt [IMathDelimiter](../imathdelimiter)
* namnrymd [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->