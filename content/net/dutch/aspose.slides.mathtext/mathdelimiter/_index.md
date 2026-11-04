---
title: MathDelimiter
second_title: Aspose.Sildes voor .NET API-referentie
description: Specificeert het scheidingstekenobject dat bestaat uit opening- en sluittekens zoals haakjes, accolades, vierkante haakjes en verticale strepen, en één of meer wiskundige elementen binnen, gescheiden door een opgegeven teken. Voorbeelden 2 2x7C2
type: docs
weight: 8670
url: /nl/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter klasse

Specificeert het scheidingstekenobject, bestaande uit opening- en sluittekens (zoals haakjes, accolades, vierkante haakjes en verticale strepen), en één of meer wiskundige elementen binnen, gescheiden door een opgegeven teken. Voorbeelden: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | Initialiseert MathDelimiter met het opgegeven element als enkel basisargument |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | Een of meer wiskundige elementen gescheiden door scheidingstekenkarakters |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Delimiter Beginning Character specificeert het begin-, of openings-, scheidingstekenkarakter. Wiskundige scheidingstekens zijn omsluitende tekens zoals haakjes, vierkante haakjes en accolades. Standaard: '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | Specifies the shape of delimiters in the delimiter object. When is MathDelimiterShape.Centered, delimiters are centered around the math axis of the mathematical text and still be made to fit the entire height of their contents. When is MathDelimiterShape.Match, their height and shape are altered to exactly match their contents. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Delimiter Ending Character specificeert het eind-, of sluit-, scheidingstekenkarakter. Wiskundige scheidingstekens zijn omsluitende tekens zoals haakjes, vierkante haakjes en accolades. Standaard: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. The default value is true |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Delimiter Separator Character specificeert het teken dat argumenten scheidt in het delimiterobject. Standaard: '&#x7C;'. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Stelt een accentteken in (een teken boven dit element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt en een opgegeven extra argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt en een opgegeven extra argument |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | Scheidt argumenten met het opgegeven scheidingstekenkarakter |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Maakt een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Maakt een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omvat een wiskundig element in haakjes |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | Omvat een wiskundig element met opgegeven tekens zoals haakjes of andere tekens als kader |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | Haalt kindelementen op |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Plaatst dit element in een groep met een onderste accolade |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Plaatst dit element in een groep met een groepeerteken zoals een onderste accolade of een ander teken |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Neemt de integraal zonder grenzen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Neemt de integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Neemt de integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Neemt de integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Neemt de integraal |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Voegt een wiskundige tekst samen en vormt een wiskundig blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Maakt een N-aire operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Maakt een N-aire operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Plaatst een balk boven dit element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specificeert de wiskundige wortel van de opgegeven graad vanuit het gespecificeerde argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specificeert de wiskundige wortel van de opgegeven graad vanuit het gespecificeerde argument. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Neemt ondergrens |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Neemt ondergrens |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Maakt subscript |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Maakt subscript |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Plaatst dit element in een niet-visuele box (logische groepering) die wordt gebruikt om componenten van een vergelijking of andere wiskundige tekst te groeperen. Een ingekaderd object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, dienen als een regeleindepunt, of zo worden gegroepeerd dat geen regeleinden binnen toegestaan zijn. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Plaatst in een verticale reeks |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Plaatst een balk onder dit element |

### Voorbeelden

Example:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### Zie ook

* klasse [MathElementBase](../mathelementbase)
* interface [IMathDelimiter](../imathdelimiter)
* naamruimte [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->