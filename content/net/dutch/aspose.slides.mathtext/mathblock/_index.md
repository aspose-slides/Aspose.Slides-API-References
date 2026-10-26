---
title: MathBlock
second_title: Aspose.Sildes voor .NET API-referentie
description: Specificeert een instantie van wiskundige tekst die zich binnen een MathParagraph bevindt en op een eigen regel begint. Alle wiskundige zones, inclusief vergelijkingen, uitdrukkingen, reeksen van vergelijkingen of uitdrukkingen en formules, worden weergegeven door een math-blok.
type: docs
weight: 8590
url: /nl/aspose.slides.mathtext/mathblock/
---
## MathBlock klasse

Specificeert een instantie van wiskundige tekst die zich binnen een MathParagraph bevindt en op een eigen regel begint. Alle wiskundige zones, inclusief vergelijkingen, uitdrukkingen, reeksen van vergelijkingen of uitdrukkingen, en formules worden weergegeven door een math-blok.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Constructoren

| Naam | Beschrijving |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Initialiseert een nieuw exemplaar van de MathBlock klasse. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Maakt een nieuw wiskundig blok en plaatst de opgegeven elementen erin |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Maakt een nieuw wiskundig blok en plaatst het opgegeven element erin |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Haalt het aantal onderliggende wiskundige elementen op dat daadwerkelijk in de collectie zit. Alleen-lezen Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Geeft false terug omdat de collectie van onderliggende elementen kan worden gewijzigd. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Haalt op of stelt IMathElement in op de opgegeven index. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Stelt een accentteken (een teken boven dit element) in |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Voegt een wiskundig element toe aan het einde van de collectie. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Neemt de opgegeven functie met dit exemplaar als argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Neemt de opgegeven functie met dit exemplaar als argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Neemt de opgegeven functie met dit exemplaar als argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Neemt de opgegeven functie met dit exemplaar als argument en een extra opgegeven argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Neemt de opgegeven functie met dit exemplaar als argument en een extra opgegeven argument |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Verwijdert alle elementen uit de collectie. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Bepaalt of de collectie een specifieke waarde bevat. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Kopieert naar de opgegeven array. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Scheidt onderliggende elementen met een scheidingsteken (zonder haakjes) |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Maakt een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Maakt een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Maakt een breuk van het opgegeven type met deze teller en opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Maakt een breuk van het opgegeven type met deze teller en opgegeven noemer |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Plaatst een wiskundig element tussen haakjes |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Plaatst onderliggende elementen van dit blok tussen de opgegeven tekens, bijvoorbeeld haakjes of andere kadertekens |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Plaatst onderliggende elementen van dit blok tussen de opgegeven tekens en scheidt ze met een scheidingsteken |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Neemt een functie van een argument met dit exemplaar als functienaam |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Neemt een functie van een argument met dit exemplaar als functienaam |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Haalt onderliggende elementen op |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Plaatst dit element in een groep met een onderste accolade |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Plaatst dit element in een groep met een groepeerteken, bijvoorbeeld een onderste accolade of een ander teken |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Bepaalt de index van een specifiek wiskundig element in de collectie. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Voegt een MathElement in de collectie in op de opgegeven index. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Neemt het integraal zonder limieten |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Neemt het integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Neemt het integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Neemt het integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Neemt het integraal |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Voegt een wiskundig element samen met dit wiskundige blok |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Voegt een wiskundige tekst samen met dit wiskundige blok |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Voegt een ander wiskundig blok samen met dit blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Maakt een N-aire operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Maakt een N-aire operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Plaatst een balk boven dit element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Bepaalt de wiskundige wortel van de opgegeven graad uit het opgegeven argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Bepaalt de wiskundige wortel van de opgegeven graad uit het opgegeven argument. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Verwijdert de eerste vindplaats van een specifiek object uit de collectie. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Verwijdert het element op de opgegeven index van de collectie. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Neemt limiet onder |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Neemt limiet onder |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Maakt subscript |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Maakt subscript |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Maakt subscript en superscript links |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Maakt subscript en superscript links |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Maakt subscript en superscript rechts |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Maakt subscript en superscript rechts |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Maakt superscript |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Maakt superscript |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Neemt limiet boven |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Neemt limiet boven |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Plaatst dit element in een kader-vak |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Plaatst dit element in een kader-vak |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Plaatst dit element in een niet-visueel vak (logische groepering) dat wordt gebruikt om componenten van een vergelijking of andere wiskundige tekst te groeperen. Een ingesloten object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder uitlijningspunt, als een regelonderbrekpunt, of gegroepeerd worden zodat er geen regelonderbrekingen binnen plaatsvinden. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Plaatst onderliggende elementen in een verticale rij |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Plaatst een balk onder dit element |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Slaat de inhoud van deze [`MathBlock`](../mathblock) op als MathML |

### Voorbeelden

Voorbeeld:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Zie ook

* klasse [MathElementBase](../mathelementbase)
* interface [IMathBlock](../imathblock)
* naamruimte [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->