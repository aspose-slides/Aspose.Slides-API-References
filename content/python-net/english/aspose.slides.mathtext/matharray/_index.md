---
title: MathArray class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/
---


## MathArray class

Specifies a vertical array of equations or any mathematical objects

**Inheritance:**[`MathArray`](/slides/python-net/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)

The MathArray type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#IMathElement) | Creates a mathematical array and places the specified element in it |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#Iterable[IMathElement]) |  |

## Properties

| Property | Description |
| :- | :- |
| [arguments](/slides/python-net/aspose.slides.mathtext/arguments) | The set of items of the array |
| [base_justification](/slides/python-net/aspose.slides.mathtext/base_justification) | Specifies alignment of the array relative to surrounding text<br/>            Text outside of the array can be aligned with the bottom, top, or center of a array object.<br/>            Default value: Center |
| [maximum_distribution](/slides/python-net/aspose.slides.mathtext/maximum_distribution) | Maximum Distribution<br/>            When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.). |
| [object_distribution](/slides/python-net/aspose.slides.mathtext/object_distribution) | Object Distribution<br/>            When true, the contents of the array are spaced to the maximum width of the array object. |
| [row_spacing_rule](/slides/python-net/aspose.slides.mathtext/row_spacing_rule) | The type of vertical spacing between array elements<br/>            Default: SingleLineGap |
| [row_spacing](/slides/python-net/aspose.slides.mathtext/row_spacing) | Spacing between rows of an array<br/>            It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points <br/>            or Multiple in which case the unit of measure is half-lines.<br/>            Default: 0 |
| [as_i_math_element](/slides/python-net/aspose.slides.mathtext/as_i_math_element) |  |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#IMathElement) | Joins a mathematical element and forms a mathematical block |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#string) | Joins a mathematical text and forms a mathematical block |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#IMathElement) | Creates a fraction with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#string) | Creates a fraction with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#IMathElement-MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#string-MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#) | Encloses a math element in parenthesis |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#char-char) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#IMathElement) | Takes a function of an argument using this instance as the function name |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#string) | Takes a function of an argument using this instance as the function name |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#IMathElement) | Takes specified function using this instance as the argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#string) | Takes specified function using this instance as the argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#MathFunctionsOfOneArgument) | Takes specified function using this instance as the argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#MathFunctionsOfTwoArguments-IMathElement) | Takes specified function using this instance as the argument and specified additional argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#MathFunctionsOfTwoArguments-string) | Takes specified function using this instance as the argument and specified additional argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#IMathElement) | Creates subscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#string) | Creates subscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#IMathElement) | Creates superscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#string) | Creates superscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#IMathElement-IMathElement) | Creates subscript and superscript on the right |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#string-string) | Creates subscript and superscript on the right |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#IMathElement-IMathElement) | Creates subscript and superscript on the left |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#string-string) | Creates subscript and superscript on the left |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#IMathElement) | Specifies the mathematical root of the given degree from the specified argument. |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#string) | Specifies the mathematical root of the given degree from the specified argument. |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#IMathElement) | Takes upper limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#string) | Takes upper limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#IMathElement) | Takes lower limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#string) | Takes lower limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#MathNaryOperatorTypes-IMathElement-IMathElement) | Creates a N-ary operator |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#MathNaryOperatorTypes-string-string) | Creates a N-ary operator |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#MathIntegralTypes-IMathElement-IMathElement-MathLimitLocations) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#MathIntegralTypes-IMathElement-IMathElement) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#MathIntegralTypes) | Takes the integral without limits |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#MathIntegralTypes-string-string-MathLimitLocations) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#MathIntegralTypes-string-string) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#) | Places this element in a group using a bottom curly bracket |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#char-MathTopBotPositions-MathTopBotPositions) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#) | Places this element in a border-box |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#bool-bool-bool-bool-bool-bool-bool-bool) | Places this element in a border-box |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#) | Puts in a vertical array |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#char) | Sets an accent mark (a character on the top of this element) |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#) | Sets a bar on the top of this element |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#) | Sets a bar on the bottom of this element |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#) | Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within. |
| [__init__](/slides/python-net/aspose.slides.mathtext/matharray/#) | Get children elements |

