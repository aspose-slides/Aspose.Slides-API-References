---
title: MathElementBase
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 7950
url: /net/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase class

Base class for IMathElement with the implementation of some methods that are common to all inherited classes For internal use only. Inherited class must be IMathElement.

```csharp
public abstract class MathElementBase : IMathElement
```

## Methods

| Name | Description |
| --- | --- |
| [Accent](accent)(char) | Sets an accent mark (a character on the top of this element) |
| [AsArgumentOfFunction](asargumentoffunction)(IMathElement) | Takes specified function using this instance as the argument |
| [AsArgumentOfFunction](asargumentoffunction)(MathFunctionsOfOneArgument) | Takes specified function using this instance as the argument |
| [AsArgumentOfFunction](asargumentoffunction)(string) | Takes specified function using this instance as the argument |
| [AsArgumentOfFunction](asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Takes specified function using this instance as the argument and specified additional argument |
| [AsArgumentOfFunction](asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Takes specified function using this instance as the argument and specified additional argument |
| [Divide](divide)(IMathElement) | Creates a fraction with this numerator and specified denominator |
| [Divide](divide)(string) | Creates a fraction with this numerator and specified denominator |
| [Divide](divide)(IMathElement, MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [Divide](divide)(string, MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [Enclose](enclose)() | Encloses a math element in parenthesis |
| virtual [Enclose](enclose)(char, char) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [Function](function)(IMathElement) | Takes a function of an argument using this instance as the function name |
| [Function](function)(string) | Takes a function of an argument using this instance as the function name |
| [Group](group)() | Places this element in a group using a bottom curly bracket |
| [Group](group)(char, MathTopBotPositions, MathTopBotPositions) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [Integral](integral)(MathIntegralTypes) | Takes the integral without limits |
| [Integral](integral)(MathIntegralTypes, IMathElement, IMathElement) | Takes the integral |
| [Integral](integral)(MathIntegralTypes, string, string) | Takes the integral |
| [Integral](integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Takes the integral |
| [Integral](integral)(MathIntegralTypes, string, string, MathLimitLocations) | Takes the integral |
| virtual [Join](join)(IMathElement) | Joins a mathematical element and forms a mathematical block |
| virtual [Join](join)(string) | Joins a mathematical text and forms a mathematical block |
| [Nary](nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Creates a N-ary operator |
| [Nary](nary)(MathNaryOperatorTypes, string, string) | Creates a N-ary operator |
| [Overbar](overbar)() | Sets a bar on the top of this element |
| [Radical](radical)(IMathElement) | Specifies the mathematical root of the given degree from the specified argument. |
| [Radical](radical)(string) | Specifies the mathematical root of the given degree from the specified argument. |
| [SetLowerLimit](setlowerlimit)(IMathElement) | Takes lower limit |
| [SetLowerLimit](setlowerlimit)(string) | Takes lower limit |
| [SetSubscript](setsubscript)(IMathElement) | Creates subscript |
| [SetSubscript](setsubscript)(string) | Creates subscript |
| [SetSubSuperscriptOnTheLeft](setsubsuperscriptontheleft)(IMathElement, IMathElement) | Creates subscript and superscript on the left |
| [SetSubSuperscriptOnTheLeft](setsubsuperscriptontheleft)(string, string) | Creates subscript and superscript on the left |
| [SetSubSuperscriptOnTheRight](setsubsuperscriptontheright)(IMathElement, IMathElement) | Creates subscript and superscript on the right |
| [SetSubSuperscriptOnTheRight](setsubsuperscriptontheright)(string, string) | Creates subscript and superscript on the right |
| [SetSuperscript](setsuperscript)(IMathElement) | Creates superscript |
| [SetSuperscript](setsuperscript)(string) | Creates superscript |
| [SetUpperLimit](setupperlimit)(IMathElement) | Takes upper limit |
| [SetUpperLimit](setupperlimit)(string) | Takes upper limit |
| [ToBorderBox](toborderbox)() | Places this element in a border-box |
| [ToBorderBox](toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Places this element in a border-box |
| [ToBox](tobox)() | Places this element in a non-visual box (logical grouping) which is used to group components of an equation or other instance of mathematical text. A boxed object can (for example) serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within. |
| virtual [ToMathArray](tomatharray)() | Puts in a vertical array |
| [Underbar](underbar)() | Sets a bar on the bottom of this element |

### See Also

* interface [IMathElement](../imathelement)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
