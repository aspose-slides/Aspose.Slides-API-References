---
title: MathDelimiter
second_title: Aspose.Sildes voor .NET API-referentie
description: Specificeert het delimiterobject bestaande uit opening- en sluitingskarakters zoals haakjes, accolades, vierkante haken en verticale strepen, en een of meer wiskundige elementen erin, gescheiden door een opgegeven karakter. Voorbeelden 2 2x7C2
type: docs
weight: 8650
url: /nl/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter klasse

Specificeert het delimiterobject, bestaande uit openings- en sluitingstekens (zoals haakjes, accolades, vierkante haken en verticale strepen), en een of meer wiskundige elementen erin, gescheiden door een opgegeven teken. Voorbeelden: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | Initialiseert MathDelimiter met het opgegeven element als enkel basiselement |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | Een of meer wiskundige elementen gescheiden door delimitertekens |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Delimiter Beginning Character specificeert het begin-, of openings- delimiterteken. Wiskundige delimiters zijn omsluitende tekens zoals haakjes, vierkante haken en accolades. Standaard: '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | Specificeert de vorm van delimiters in het delimiterobject. Wanneer MathDelimiterShape.Centered, worden delimiters gecentreerd rond de wiskunde-as van de wiskundige tekst en worden ze aangepast om de volledige hoogte van hun inhoud te passen. Wanneer MathDelimiterShape.Match, worden hun hoogte en vorm aangepast om exact overeen te komen met hun inhoud. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Delimiter Ending Character specificeert het eind-, of sluitings- delimiterteken. Wiskundige delimiters zijn omsluitende tekens zoals haakjes, vierkante haken en accolades. Standaard: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de delimiters verticaal om overeen te komen met de hoogte van hun operand. Standaardwaarde is true |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Delimiter Separator Character specificeert het teken dat argumenten scheidt in het delimiterobject. Standaard: '&#x7C;'. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Stelt een accentteken in (een teken bovenop dit element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt en een opgegeven extra argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt en een opgegeven extra argument |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | Delimeert argumenten met het opgegeven delimiterteken |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Maakt een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Maakt een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omringt een wiskundig element met haakjes |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | Omringt een wiskundig element met opgegeven tekens, zoals haakjes of andere tekens als omlijsting |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Neemt een functie van een argument waarbij dit exemplaar als functienaam wordt gebruikt |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Neemt een functie van een argument waarbij dit exemplaar als functienaam wordt gebruikt |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | Verkrijgt kindelementen |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Plaatst dit element in een groep met een onderste accolade |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Plaatst dit element in een groep met een groepeerteken, zoals een onderste accolade of een ander teken |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Neemt de integraal zonder grenzen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Neemt de integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Neemt de integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Neemt de integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Neemt de integraal |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Voegt een wiskundige tekst samen en vormt een wiskundig blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Maakt een N-ary operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Maakt een N-ary operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Stelt een balk bovenop dit element in |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specificeert de wiskundige wortel van de gegeven graad vanuit het opgegeven argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specificeert de wiskundige wortel van de gegeven graad vanuit het opgegeven argument. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Neemt onderlimiet |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Neemt onderlimiet |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Plaatst dit element in een niet-visueel vak (logische groepering) dat wordt gebruikt om componenten van een vergelijking of andere wiskundige tekst te groeperen. Een ingekaderd object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder uitlijningspunt, dienen als een regelafbreekpunt, of gegroepeerd worden zodat geen regelafbrekingen binnen mogelijk zijn. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Plaatst in een verticale array |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Stelt een balk onderaan dit element in |

### Voorbeelden

Voorbeeld:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### Zie ook

* klasse [MathElementBase](../mathelementbase)
* interface [IMathDelimiter](../imathdelimiter)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->