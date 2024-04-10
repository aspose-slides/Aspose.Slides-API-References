---
title: IMathBox class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/
---


## IMathBox class

Specifies the logical boxing (packaging) of mathematical element.
            For example, a boxed object can serve as an operator emulator with or without an alignment point, 
            serve as a line break point, or be grouped such as not to allow line breaks within.
            For example, the "==" operator should be boxed to prevent line breaks.

The IMathBox type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [base](/slides/python-net/aspose.slides.mathtext/base) | Base argument |
| [operator_emulator](/slides/python-net/aspose.slides.mathtext/operator_emulator) | Operator Emulator.<br/>            When true, the box and its contents behave as a single operator and inherit the properties of an operator. <br/>            This means, for example, that the character can serve as a point for a line break and can be aligned to other operators.<br/>            Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='.<br/>            Default value: false |
| [no_break](/slides/python-net/aspose.slides.mathtext/no_break) | No break.<br/>            This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box.<br/>            This can be important for operator emulators that consist of more than one binary operator. <br/>            When this element is not specified, breaks can occur inside box.<br/>            Default: true |
| [differential](/slides/python-net/aspose.slides.mathtext/differential) | Differential.<br/>            When true, the box acts as a differential (e.g., 𝑑𝑥 in an integrand), and receives the appropriate <br/>            horizontal spacing for the mathematical differential.<br/>            Default: false |
| [alignment_point](/slides/python-net/aspose.slides.mathtext/alignment_point) | When true, this operator emulator serves as an alignment point; that is, <br/>            designated alignment points in other equations can be aligned with it.<br/>            Default: false |
| [explicit_break](/slides/python-net/aspose.slides.mathtext/explicit_break) | Explicit break specifies whether there is a line break at the start of the Box object, <br/>            such that the line wraps at the start of the box object.<br/>            Specifies the number of the operator on the previous line of mathematical text which shall<br/>            be used as the alignment point for the current line of mathematical text<br/>            possible values: 1..255<br/>            Default: 0 (no explicit break) |
| [as_i_math_element](/slides/python-net/aspose.slides.mathtext/as_i_math_element) | Allows to get base IMathElement interface<br/>            :py:class:`aspose.slides.mathtext.IMathElement` |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#IMathElement-MathFractionTypes) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#string-MathFractionTypes) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#char-char) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#MathFunctionsOfOneArgument) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#MathFunctionsOfTwoArguments-IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#MathFunctionsOfTwoArguments-string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#IMathElement-IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#string-string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#IMathElement-IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#string-string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#MathNaryOperatorTypes-IMathElement-IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#MathNaryOperatorTypes-string-string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#MathIntegralTypes-IMathElement-IMathElement-MathLimitLocations) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#MathIntegralTypes-IMathElement-IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#MathIntegralTypes) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#MathIntegralTypes-string-string-MathLimitLocations) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#MathIntegralTypes-string-string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#char-MathTopBotPositions-MathTopBotPositions) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#char) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathbox/#) |  |

