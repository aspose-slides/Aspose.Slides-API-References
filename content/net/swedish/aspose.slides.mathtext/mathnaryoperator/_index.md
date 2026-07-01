---
title: MathNaryOperator
second_title: Aspose.Sildes för .NET API-referens
description: Specificerar ett N-ary matematiskt objekt såsom Summation och Integral. Det består av en operator, en bas eller operand och valfria övre och nedre gränser. Exempel på N-ary-operatorer är Summation, Union, Intersection, Integral
type: docs
weight: 8850
url: /sv/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator klass

Specificerar ett N-ary matematiskt objekt, såsom Summation och Integral. Den består av en operator, en bas (eller operand), och valfria övre och nedre gränser. Exempel på N-ary-operatorer är: Summation, Union, Intersection, Integral

```csharp
public sealed class MathNaryOperator : MathElementBase, IMathNaryOperator
```

## Konstruktörer

| Name | Description |
| --- | --- |
| [MathNaryOperator](mathnaryoperator#constructor)(char, IMathElement) | Initierar en ny instans av MathNaryOperator klass. |
| [MathNaryOperator](mathnaryoperator#constructor_1)(char, IMathElement, IMathElement) | Initierar en ny instans av MathNaryOperator klass. |
| [MathNaryOperator](mathnaryoperator#constructor_2)(char, IMathElement, IMathElement, IMathElement) | Initierar en ny instans av MathNaryOperator klass. |

## Egenskaper

| Name | Description |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathnaryoperator/base) { get; } | Basargument |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathnaryoperator/growtomatchoperandheight) { get; set; } | Operatorns tecken växer vertikalt för att matcha operandens höjd |
| [HideSubscript](../../aspose.slides.mathtext/mathnaryoperator/hidesubscript) { get; set; } | Dölj subscript |
| [HideSuperscript](../../aspose.slides.mathtext/mathnaryoperator/hidesuperscript) { get; set; } | Dölj superscript |
| [LimitLocation](../../aspose.slides.mathtext/mathnaryoperator/limitlocation) { get; set; } | Placeringen av gränser (subscript och superscript) |
| [Operator](../../aspose.slides.mathtext/mathnaryoperator/operator) { get; set; } | Nary-operator tecken Till exempel: '∑', '∫' |
| [Subscript](../../aspose.slides.mathtext/mathnaryoperator/subscript) { get; } | Anger ett subscript-argument som till exempel i fallet med en integral sätter den nedre gränsen |
| [Superscript](../../aspose.slides.mathtext/mathnaryoperator/superscript) { get; } | Anger ett superscript-argument som till exempel i fallet med en integral sätter den övre gränsen |

## Metoder

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ställer in ett accenttecken (ett tecken ovanpå detta element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Tar en specificerad funktion med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Tar en specificerad funktion med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Tar en specificerad funktion med detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Tar en specificerad funktion med detta objekt som argument och ett specificerat ytterligare argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Tar en specificerad funktion med detta objekt som argument och ett specificerat ytterligare argument |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Skapar en bråkdel med detta täljare och specificerad nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Skapar en bråkdel med detta täljare och specificerad nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Skapar ett bråk av den specificerade typen med detta täljare och specificerad nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Skapar ett bråk av den specificerade typen med detta täljare och specificerad nämnare |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omger ett matematikelement med parenteser |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Omger ett matematikelement med specificerade tecken såsom parenteser eller andra tecken som ram |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [GetChildren](../../aspose.slides.mathtext/mathnaryoperator/getchildren)() | Hämtar underordnade element |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Placera detta element i en grupp med en nedre måsvinge |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Placera detta element i en grupp med ett grupperingstecken såsom nedre måsvinge eller annat |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Tar integralen utan gränser |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Tar integralen |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Förena ett matematikelement och bilda ett matematiskt block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Förena en matematisk text och bilda ett matematiskt block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Skapar en N-ary operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Skapar en N-ary operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Sätter en stapel på toppen av detta element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Anger den matematiska roten av given grad från angivet argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Anger den matematiska roten av given grad från angivet argument. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Tar nedre gräns |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Tar nedre gräns |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Skapar subscript |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Skapar subscript |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Skapar subscript och superscript till vänster |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Skapar subscript och superscript till vänster |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Skapar subscript och superscript till höger |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Skapar subscript och superscript till höger |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Skapar superscript |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Skapar superscript |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Tar övre gräns |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Tar övre gräns |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Placera detta element i en kantbox |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Placera detta element i en kantbox |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Placera detta element i en icke-visuell ruta (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan matematisk text. En ruta kan (till exempel) fungera som en operator-emulator med eller utan justeringspunkt, fungera som ett radbrytning-punkt eller grupperas så att radbrytningar inte tillåts inom den. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Sätter i en vertikal array |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Sätter en stapel på botten av detta element |

### Exempel

Example:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### Se även

* klass [MathElementBase](../mathelementbase)
* interface [IMathNaryOperator](../imathnaryoperator)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->