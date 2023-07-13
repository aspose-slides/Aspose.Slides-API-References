---
title: MathRadical
second_title: Aspose.Sildes for .NET API Reference
description: Specifies the radical function consisting of a base and an optional degree. Example of radical object is .
type: docs
weight: 8340
url: /net/aspose.slides.mathtext/mathradical/
---
## MathRadical class

Specifies the radical function, consisting of a base, and an optional degree. Example of radical object is √𝑥.

```csharp
public sealed class MathRadical : MathElementBase, IMathRadical
```

## Constructors

| Name | Description |
| --- | --- |
| [MathRadical](mathradical)(IMathElement, IMathElement) | Initializes a new instance of the MathRadical class. |

## Properties

| Name | Description |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathradical/base) { get; } | Base argument |
| [Degree](../../aspose.slides.mathtext/mathradical/degree) { get; } | Degree argument |
| [HideDegree](../../aspose.slides.mathtext/mathradical/hidedegree) { get; set; } | Hide degree When is true, the degree is not shown, as in √𝑥 |

## Methods

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Sets an accent mark (a character on the top of this element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Takes specified function using this instance as the argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Takes specified function using this instance as the argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Takes specified function using this instance as the argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Takes specified function using this instance as the argument and specified additional argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Takes specified function using this instance as the argument and specified additional argument |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Creates a fraction with this numerator and specified denominator |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Creates a fraction with this numerator and specified denominator |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Encloses a math element in parenthesis |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Takes a function of an argument using this instance as the function name |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Takes a function of an argument using this instance as the function name |
| [GetChildren](../../aspose.slides.mathtext/mathradical/getchildren)() | Get children elements |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Places this element in a group using a bottom curly bracket |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Takes the integral without limits |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Takes the integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Takes the integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Takes the integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Takes the integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Joins a mathematical element and forms a mathematical block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Joins a mathematical text and forms a mathematical block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Creates a N-ary operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Creates a N-ary operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Sets a bar on the top of this element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specifies the mathematical root of the given degree from the specified argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specifies the mathematical root of the given degree from the specified argument. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Takes lower limit |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Takes lower limit |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Creates subscript |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Creates subscript |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Creates subscript and superscript on the left |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Creates subscript and superscript on the left |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Creates subscript and superscript on the right |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Creates subscript and superscript on the right |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Creates superscript |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Creates superscript |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Takes upper limit |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Takes upper limit |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Places this element in a border-box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Places this element in a border-box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Places this element in a non-visual box (logical grouping) which is used to group components of an equation or other instance of mathematical text. A boxed object can (for example) serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Puts in a vertical array |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Sets a bar on the bottom of this element |

### Examples

Example:

```csharp
[C#]
MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
```

### See Also

* class [MathElementBase](../mathelementbase)
* interface [IMathRadical](../imathradical)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
