---
title: MathBox class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/
---


## MathBox class

Specifies the logical boxing (packaging) of mathematical element.
            For example, a boxed object can serve as an operator emulator with or without an alignment point, 
            serve as a line break point, or be grouped such as not to allow line breaks within.
            For example, the "==" operator should be boxed to prevent line breaks.

**Inheritance:**[`MathBox`](/slides/python-net/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)

The MathBox type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#IMathElement) | Initializes MathBox with the specified element as an argument |

## Properties

| Property | Description |
| :- | :- |
| [base](/slides/python-net/aspose.slides.mathtext/base) | Base argument |
| [operator_emulator](/slides/python-net/aspose.slides.mathtext/operator_emulator) | Operator Emulator.<br/>            When true, the box and its contents behave as a single operator and inherit the properties of an operator. <br/>            This means, for example, that the character can serve as a point for a line break and can be aligned to other operators.<br/>            Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='.<br/>            Default value: false |
| [no_break](/slides/python-net/aspose.slides.mathtext/no_break) | No break<br/>            This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box.<br/>            This can be important for operator emulators that consist of more than one binary operator. <br/>            When this element is not specified, breaks can occur inside box.<br/>            Default: true |
| [differential](/slides/python-net/aspose.slides.mathtext/differential) | Differential<br/>            When true, the box acts as a differential (e.g., 𝑑𝑥 in an integrand), and receives the appropriate <br/>            horizontal spacing for the mathematical differential.<br/>            Default: false |
| [alignment_point](/slides/python-net/aspose.slides.mathtext/alignment_point) | When true, this operator emulator serves as an alignment point; that is, <br/>            designated alignment points in other equations can be aligned with it.<br/>            Default: false |
| [explicit_break](/slides/python-net/aspose.slides.mathtext/explicit_break) | Explicit break specifies whether there is a line break at the start of the Box object, <br/>            such that the line wraps at the start of the box object.<br/>            Specifies the number of the operator on the previous line of mathematical text which shall<br/>            be used as the alignment point for the current line of mathematical text<br/>            possible values: 1..255<br/>            Default: 0 (no explicit break) |
| [as_i_math_element](/slides/python-net/aspose.slides.mathtext/as_i_math_element) |  |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#IMathElement) | Joins a mathematical element and forms a mathematical block |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#string) | Joins a mathematical text and forms a mathematical block |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#IMathElement) | Creates a fraction with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#string) | Creates a fraction with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#IMathElement-MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#string-MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#) | Encloses a math element in parenthesis |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#char-char) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#IMathElement) | Takes a function of an argument using this instance as the function name |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#string) | Takes a function of an argument using this instance as the function name |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#IMathElement) | Takes specified function using this instance as the argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#string) | Takes specified function using this instance as the argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#MathFunctionsOfOneArgument) | Takes specified function using this instance as the argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#MathFunctionsOfTwoArguments-IMathElement) | Takes specified function using this instance as the argument and specified additional argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#MathFunctionsOfTwoArguments-string) | Takes specified function using this instance as the argument and specified additional argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#IMathElement) | Creates subscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#string) | Creates subscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#IMathElement) | Creates superscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#string) | Creates superscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#IMathElement-IMathElement) | Creates subscript and superscript on the right |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#string-string) | Creates subscript and superscript on the right |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#IMathElement-IMathElement) | Creates subscript and superscript on the left |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#string-string) | Creates subscript and superscript on the left |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#IMathElement) | Specifies the mathematical root of the given degree from the specified argument. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#string) | Specifies the mathematical root of the given degree from the specified argument. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#IMathElement) | Takes upper limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#string) | Takes upper limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#IMathElement) | Takes lower limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#string) | Takes lower limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#MathNaryOperatorTypes-IMathElement-IMathElement) | Creates a N-ary operator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#MathNaryOperatorTypes-string-string) | Creates a N-ary operator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#MathIntegralTypes-IMathElement-IMathElement-MathLimitLocations) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#MathIntegralTypes-IMathElement-IMathElement) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#MathIntegralTypes) | Takes the integral without limits |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#MathIntegralTypes-string-string-MathLimitLocations) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#MathIntegralTypes-string-string) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#) | Places this element in a group using a bottom curly bracket |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#char-MathTopBotPositions-MathTopBotPositions) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#) | Places this element in a border-box |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#bool-bool-bool-bool-bool-bool-bool-bool) | Places this element in a border-box |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#) | Puts in a vertical array |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#char) | Sets an accent mark (a character on the top of this element) |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#) | Sets a bar on the top of this element |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#) | Sets a bar on the bottom of this element |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#) | Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathbox/#) | Get children elements |

