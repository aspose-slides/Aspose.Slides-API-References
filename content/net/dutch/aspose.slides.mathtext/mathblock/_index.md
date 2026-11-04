---
title: MathBlock
second_title: Aspose.Sildes voor .NET API-referentie
description: Specificeert een instantie van wiskundige tekst die zich bevindt binnen een MathParagraph en op een eigen regel begint. Alle wiskundige zones, inclusief vergelijkingen, uitdrukkingen, arrays van vergelijkingen of uitdrukkingen en formules, worden weergegeven door een wiskundig blok.
type: docs
weight: 8610
url: /nl/aspose.slides.mathtext/mathblock/
---
## MathBlock klasse

Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line. All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Constructors

| Name | Description |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Initialiseert een nieuw exemplaar van de MathBlock klasse. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Creëert een nieuw wiskundig blok en plaatst de opgegeven elementen erin |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Creëert een nieuw wiskundig blok en plaatst het opgegeven element erin |

## Eigenschappen

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Geeft het aantal onderliggende wiskunde-elementen dat daadwerkelijk in de collectie zit. Alleen-lezen Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Geeft false terug omdat de collectie van onderliggende elementen kan worden gewijzigd. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Geeft een IMathElement op de opgegeven index terug of stelt deze in. |

## Methoden

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Stelt een accentteken in (een teken boven dit element) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Voegt een wiskundig element toe aan het einde van de collectie. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Neemt de gespecificeerde functie waarbij dit exemplaar als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Neemt de gespecificeerde functie waarbij dit exemplaar als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Neemt de gespecificeerde functie waarbij dit exemplaar als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Neemt de gespecificeerde functie waarbij dit exemplaar als argument en een gespecificeerd extra argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Neemt de gespecificeerde functie waarbij dit exemplaar als argument en een gespecificeerd extra argument wordt gebruikt |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Verwijdert alle elementen uit de collectie. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Bepaalt of de collectie een specifieke waarde bevat. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Kopieert naar de opgegeven array. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Scheidt onderliggende elementen met een scheidingsteken (zonder de haakjes) |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Maakt een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Maakt een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Maakt een breuk van het opgegeven type met deze teller en opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Maakt een breuk van het opgegeven type met deze teller en opgegeven noemer |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omgeeft een wiskundig element met haakjes |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Omgeeft onderliggende elementen van dit blok met de opgegeven tekens, zoals haakjes of andere tekens als omlijsting |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Omgeeft onderliggende elementen van dit blok met de opgegeven tekens, zoals haakjes of andere, en scheidt ze met een scheidingsteken |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Neemt een functie van een argument waarbij dit exemplaar als functienaam wordt gebruikt |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Neemt een functie van een argument waarbij dit exemplaar als functienaam wordt gebruikt |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Haalt onderliggende elementen op |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Plaatst dit element in een groep met een onderste accolade |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Plaatst dit element in een groep met een groeppartnerteken, zoals een onderste accolade of een ander teken |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Bepaalt de index van een specifiek wiskundig element in de collectie. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Voegt een MathElement in de collectie in op de opgegeven index. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Neemt het integraal zonder limieten |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Neemt het integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Neemt het integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Neemt het integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Neemt het integraal |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Voegt een wiskundig element samen met dit wiskundige blok |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Voegt wiskundige tekst samen met dit wiskundige blok |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Voegt een ander wiskundig blok toe aan dit blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Maakt een N-ary operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Maakt een N-ary operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Stelt een balk boven dit element in |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specificeert de wiskundige wortel van de gegeven graad vanuit het opgegeven argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specificeert de wiskundige wortel van de gegeven graad vanuit het opgegeven argument. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Verwijdert het eerste voorkomen van een specifiek object uit de collectie. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Verwijdert het element op de opgegeven index van de collectie. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Neemt onderlimiet |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Neemt onderlimiet |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Maakt een subscript |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Maakt een subscript |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Maakt subscript en superscript aan de linkerkant |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Maakt subscript en superscript aan de linkerkant |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Maakt subscript en superscript aan de rechterkant |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Maakt subscript en superscript aan de rechterkant |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Maakt superscript |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Maakt superscript |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Neemt bovengrens |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Neemt bovengrens |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Plaatst dit element in een randvak |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Plaatst dit element in een randvak |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Plaatst dit element in een niet-visueel vak (logische groepering) dat wordt gebruikt om componenten van een vergelijking of andere wiskundige tekst te groeperen. Een ingesloten object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder uitlijnpunt, dienen als een regeleinde-punt, of worden gegroepeerd zodat er geen regeleinden binnen toegestaan worden. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Plaatst onderliggende elementen in een verticale reeks |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Stelt een balk onder dit element in |
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
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->