---
title: MathDelimiter
second_title: Aspose.Sildes voor .NET API-referentie
description: Specificeert het delimiterobject dat bestaat uit opening- en sluittekens zoals haakjes, accolades, vierkante haken en verticale strepen, en één of meer wiskundige elementen erin, gescheiden door een opgegeven teken. Voorbeelden 2 2x7C2
type: docs
weight: 8650
url: /nl/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter klasse

Specificeert het scheidingstekenobject, bestaande uit opening- en sluittekens (zoals haakjes, accolades, vierkante haken en verticale strepen), en een of meer wiskundige elementen erin, gescheiden door een opgegeven teken. Voorbeelden: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## Constructoren

| Naam | Beschrijving |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | Initialiseert MathDelimiter met het opgegeven element als enkel basiselement |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | Een of meer wiskundige elementen gescheiden door delimiter characters |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Delimiter Beginning Character specificeert het beginnende, oftewel openende, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. Standaard: '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | Specificeert de vorm van delimiters in het delimiter object. Wanneer MathDelimiterShape.Centered, worden delimiters gecentreerd rond de math axis van de mathematical text and still be made to fit the entire height of their contents. Wanneer MathDelimiterShape.Match, hun height and shape are altered to exactly match their contents. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Delimiter Ending Character specificeert het eind- of sluitende delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. Standaard: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de delimiters verticaal om te passen bij de operand height. Standaardwaarde is true |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Delimiter Separator Character specificeert het teken dat argumenten scheidt in het delimiter object. Standaard: '&#x7C;'. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Stelt een accent mark in (een teken boven dit element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt en een opgegeven extra argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt en een opgegeven extra argument |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | Scheidt argumenten met het opgegeven delimiter character |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Maakt een fraction met deze numerator en de opgegeven denominator |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Maakt een fraction met deze numerator en de opgegeven denominator |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Maakt een fraction van het opgegeven type met deze numerator en de opgegeven denominator |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Maakt een fraction van het opgegeven type met deze numerator en de opgegeven denominator |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omvat een math element in parentheses |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | Omvat een math element in opgegeven characters zoals parentheses of andere characters als framing |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Neemt een function of an argument waarbij deze instantie als function name wordt gebruikt |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Neemt een function of an argument waarbij deze instantie als function name wordt gebruikt |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | Haal children elements op |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Plaats dit element in een group using a bottom curly bracket |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Plaats dit element in een group using a grouping character such as bottom curly bracket or another |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Neemt het integral zonder limits |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Neemt het integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Neemt het integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Neemt het integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Neemt het integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Voegt een mathematical element together en vormt een mathematical block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Voegt een mathematical text together en vormt een mathematical block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Maakt een N-ary operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Maakt een N-ary operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Plaatst een bar on the top of this element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specificeert de mathematical root of the given degree from the specified argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specificeert de mathematical root of the given degree from the specified argument. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Neemt lower limit |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Neemt lower limit |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Maakt subscript |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Maakt subscript |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Maakt subscript en superscript aan de linkerkant |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Maakt subscript en superscript aan de linkerkant |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Maakt subscript en superscript aan de rechterkant |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Maakt subscript en superscript aan de rechterkant |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Maakt superscript |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Maakt superscript |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Neemt upper limit |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Neemt upper limit |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Plaatst dit element in een border-box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Plaatst dit element in een border-box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Plaatst dit element in een non-visual box (logical grouping) die wordt gebruikt om componenten van een vergelijking of andere wiskundige tekst te groeperen. Een ingekaderd object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, dienen als een regeleinde-punt, of worden gegroepeerd zodat geen regeleinden binnen worden toegestaan. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Plaats in een vertical array |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Plaatst een bar on the bottom of this element |

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
* naamruimte [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->