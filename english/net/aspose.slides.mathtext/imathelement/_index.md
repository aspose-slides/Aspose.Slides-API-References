---
title: IMathElement
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 7520
url: /net/aspose.slides.mathtext/imathelement/
---
## IMathElement interface

Base interface of any mathematical element: fraction, mathmatical text, function, expression with multiple elements etc

```csharp
public interface IMathElement
```

## Methods

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Sets an accent mark (a character on the top of this element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction)(IMathElement) | Takes specified function using this instance as the argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction)(MathFunctionsOfOneArgument) | Takes specified function using this instance as the argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction)(string) | Takes specified function using this instance as the argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Takes specified function using this instance as the argument and specified additional argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Takes specified function using this instance as the argument and specified additional argument |
| [Divide](../../aspose.slides.mathtext/imathelement/divide)(IMathElement) | Creates a fraction with this numerator and specified denominator |
| [Divide](../../aspose.slides.mathtext/imathelement/divide)(string) | Creates a fraction with this numerator and specified denominator |
| [Divide](../../aspose.slides.mathtext/imathelement/divide)(IMathElement, MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [Divide](../../aspose.slides.mathtext/imathelement/divide)(string, MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose)() | Encloses a math element in parenthesis |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose)(char, char) | Encloses this element in specified characters such as parenthesis or another characters as framing |
| [Function](../../aspose.slides.mathtext/imathelement/function)(IMathElement) | Takes a function of an argument using this instance as the function name |
| [Function](../../aspose.slides.mathtext/imathelement/function)(string) | Takes a function of an argument using this instance as the function name |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Get children elements |
| [Group](../../aspose.slides.mathtext/imathelement/group)() | Places this element in a group using a bottom curly bracket |
| [Group](../../aspose.slides.mathtext/imathelement/group)(char, MathTopBotPositions, MathTopBotPositions) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [Integral](../../aspose.slides.mathtext/imathelement/integral)(MathIntegralTypes) | Takes the integral without limits |
| [Integral](../../aspose.slides.mathtext/imathelement/integral)(MathIntegralTypes, IMathElement, IMathElement) | Takes the integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral)(MathIntegralTypes, string, string) | Takes the integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Takes the integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Takes the integral |
| [Join](../../aspose.slides.mathtext/imathelement/join)(IMathElement) | Joins a mathematical element and forms a mathematical block |
| [Join](../../aspose.slides.mathtext/imathelement/join)(string) | Joins a mathematical text and forms a mathematical block |
| [Nary](../../aspose.slides.mathtext/imathelement/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Creates a N-ary operator |
| [Nary](../../aspose.slides.mathtext/imathelement/nary)(MathNaryOperatorTypes, string, string) | Creates a N-ary operator |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Sets a bar on the top of this element |
| [Radical](../../aspose.slides.mathtext/imathelement/radical)(IMathElement) | Specifies the mathematical root of the given degree from the specified argument. |
| [Radical](../../aspose.slides.mathtext/imathelement/radical)(string) | Specifies the mathematical root of the given degree from the specified argument. |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit)(IMathElement) | Takes lower limit |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit)(string) | Takes lower limit |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript)(IMathElement) | Creates subscript |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript)(string) | Creates subscript |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Creates subscript and superscript on the left |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft)(string, string) | Creates subscript and superscript on the left |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright)(IMathElement, IMathElement) | Creates subscript and superscript on the right |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright)(string, string) | Creates subscript and superscript on the right |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript)(IMathElement) | Creates superscript |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript)(string) | Creates superscript |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit)(IMathElement) | Takes upper limit |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit)(string) | Takes upper limit |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox)() | Places this element in a border-box |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Places this element in a border-box |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Places this element in a non-visual box (logical grouping) which is used to group components of an equation or other instance of mathematical text. A boxed object can (for example) serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Puts in a vertical array |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Sets a bar on the bottom of this element |

### Examples

Example:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### See Also

* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
