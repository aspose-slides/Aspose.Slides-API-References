---
title: MathBlock
second_title: Aspose.Slides voor .NET API-referentie
description: Specificeert een instantie van wiskundige tekst die zich binnen een MathParagraph bevindt en op een eigen regel begint. Alle math zones, inclusief vergelijkingen, uitdrukkingen, reeksen van vergelijkingen of uitdrukkingen en formules, worden weergegeven door een math block.
type: docs
weight: 8590
url: /nl/aspose.slides.mathtext/mathblock/
---
## MathBlock klasse

Specifieert een instantie van wiskundige tekst die zich binnen een MathParagraph bevindt en op een eigen regel begint. Alle math zones, inclusief vergelijkingen, uitdrukkingen, reeksen van vergelijkingen of uitdrukkingen, en formules worden weergegeven door een math-blokken.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Constructors

| Name | Description |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Initialiseert een nieuwe instantie van de MathBlock klasse. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Maakt een nieuw wiskundig blok en plaatst de opgegeven elementen erin. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Maakt een nieuw wiskundig blok en plaatst het opgegeven element erin. |

## Eigenschappen

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Haalt het aantal onderliggende math-elementen op dat daadwerkelijk in de collectie zit. Alleen-lezen Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Retourneert false omdat de collectie van onderliggende elementen kan worden aangepast. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Haalt een IMathElement op of stelt deze in op de opgegeven index. |

## Methoden

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Stelt een accentteken in (een teken boven dit element). |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Voegt een math-element toe aan het einde van de collectie. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Neemt de opgegeven functie met deze instantie als argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Neemt de opgegeven functie met deze instantie als argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Neemt de opgegeven functie met deze instantie als argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Neemt de opgegeven functie met deze instantie als argument en een opgegeven extra argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Neemt de opgegeven functie met deze instantie als argument en een opgegeven extra argument. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Verwijdert alle elementen uit de collectie. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Bepaalt of de collectie een specifieke waarde bevat. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Kopieert naar de opgegeven array. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Beperkt onderliggende elementen met een scheidingsteken (zonder de haakjes). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Creëert een breuk met deze teller en de opgegeven noemer. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Creëert een breuk met deze teller en de opgegeven noemer. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Creëert een breuk van het opgegeven type met deze teller en opgegeven noemer. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Creëert een breuk van het opgegeven type met deze teller en opgegeven noemer. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omvat een math-element met haakjes. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Omvat onderliggende elementen van dit blok met opgegeven tekens zoals haakjes of andere tekens als omlijsting. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Omvat onderliggende elementen van dit blok met opgegeven tekens zoals haakjes of andere als omlijsting en scheidt met een scheidingsteken. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Haalt onderliggende elementen op. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Plaatst dit element in een groep met behulp van een onderste accolade. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Plaatst dit element in een groep met een groepeerteken zoals een onderste accolade of een ander teken. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Bepaalt de index van een specifiek math-element in de collectie. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Voegt een MathElement toe aan de collectie op de opgegeven index. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Neemt het integraal zonder limieten. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Neemt het integraal. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Neemt het integraal. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Neemt het integraal. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Neemt het integraal. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Voegt een wiskundig element samen met dit wiskundige blok. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Voegt wiskundige tekst samen met dit wiskundige blok. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Voegt een ander wiskundig blok samen met dit blok. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Creëert een N-aire operator. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Creëert een N-aire operator. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Plaatst een balk boven dit element. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specificeert de wiskundige wortel van de opgegeven graad van het opgegeven argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specificeert de wiskundige wortel van de opgegeven graad van het opgegeven argument. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Verwijdert de eerste voorkoming van een specifiek object uit de collectie. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Verwijdert het element op de opgegeven index van de collectie. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Neemt onderlimiet. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Neemt onderlimiet. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Creëert subscript. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Creëert subscript. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Creëert subscript en superscript aan de linkerkant. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Creëert subscript en superscript aan de linkerkant. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Creëert subscript en superscript aan de rechterkant. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Creëert subscript en superscript aan de rechterkant. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Creëert superscript. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Creëert superscript. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Neemt bovengrens. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Neemt bovengrens. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Plaatst dit element in een randvak. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Plaatst dit element in een randvak. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Plaatst dit element in een niet-visueel vak (logische groepering) dat wordt gebruikt om componenten van een vergelijking of andere wiskundige tekst te groeperen. Een ingesloten object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, dienen als een regeleinde-punt, of zo worden gegroepeerd dat geen regeleinden binnen toestaan. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Plaatst onderliggende elementen in een verticale rij. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Plaatst een balk onder dit element. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Slaat de inhoud van deze [`MathBlock`](../mathblock) op als MathML. |

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
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->