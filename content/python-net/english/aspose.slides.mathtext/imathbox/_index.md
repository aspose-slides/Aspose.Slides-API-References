---
title: IMathBox
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/imathbox/
---


IMathBox class

Specifies the logical boxing (packaging) of mathematical element.
            For example, a boxed object can serve as an operator emulator with or without an alignment point, 
            serve as a line break point, or be grouped such as not to allow line breaks within.
            For example, the "==" operator should be boxed to prevent line breaks.

The IMathBox type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [base](/slides/python-net/aspose.slides.mathtext/imathbox/base/) | Base argument |
| [operator_emulator](/slides/python-net/aspose.slides.mathtext/imathbox/operator_emulator/) | Operator Emulator.<br/>            When true, the box and its contents behave as a single operator and inherit the properties of an operator. <br/>            This means, for example, that the character can serve as a point for a line break and can be aligned to other operators.<br/>            Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='.<br/>            Default value: false |
| [no_break](/slides/python-net/aspose.slides.mathtext/imathbox/no_break/) | No break.<br/>            This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box.<br/>            This can be important for operator emulators that consist of more than one binary operator. <br/>            When this element is not specified, breaks can occur inside box.<br/>            Default: true |
| [differential](/slides/python-net/aspose.slides.mathtext/imathbox/differential/) | Differential.<br/>            When true, the box acts as a differential (e.g., 𝑑𝑥 in an integrand), and receives the appropriate <br/>            horizontal spacing for the mathematical differential.<br/>            Default: false |
| [alignment_point](/slides/python-net/aspose.slides.mathtext/imathbox/alignment_point/) | When true, this operator emulator serves as an alignment point; that is, <br/>            designated alignment points in other equations can be aligned with it.<br/>            Default: false |
| [explicit_break](/slides/python-net/aspose.slides.mathtext/imathbox/explicit_break/) | Explicit break specifies whether there is a line break at the start of the Box object, <br/>            such that the line wraps at the start of the box object.<br/>            Specifies the number of the operator on the previous line of mathematical text which shall<br/>            be used as the alignment point for the current line of mathematical text<br/>            possible values: 1..255<br/>            Default: 0 (no explicit break) |
| [as_i_math_element](/slides/python-net/aspose.slides.mathtext/imathbox/as_i_math_element/) | Allows to get base IMathElement interface<br/>            [`IMathElement`](/slides/python-net/aspose.slides.mathtext/imathelement) |

## Methods

| Method | Description |
| :- | :- |
| [join](/slides/python-net/aspose.slides.mathtext/imathbox/join/#IMathElement/) |  |
| [join](/slides/python-net/aspose.slides.mathtext/imathbox/join/#string/) |  |
| [divide](/slides/python-net/aspose.slides.mathtext/imathbox/divide/#IMathElement/) |  |
| [divide](/slides/python-net/aspose.slides.mathtext/imathbox/divide/#string/) |  |
| [divide](/slides/python-net/aspose.slides.mathtext/imathbox/divide/#IMathElement-MathFractionTypes/) |  |
| [divide](/slides/python-net/aspose.slides.mathtext/imathbox/divide/#string-MathFractionTypes/) |  |
| [enclose](/slides/python-net/aspose.slides.mathtext/imathbox/enclose/#/) |  |
| [enclose](/slides/python-net/aspose.slides.mathtext/imathbox/enclose/#char-char/) |  |
| [function](/slides/python-net/aspose.slides.mathtext/imathbox/function/#IMathElement/) |  |
| [function](/slides/python-net/aspose.slides.mathtext/imathbox/function/#string/) |  |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/imathbox/as_argument_of_function/#IMathElement/) |  |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/imathbox/as_argument_of_function/#string/) |  |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/imathbox/as_argument_of_function/#MathFunctionsOfOneArgument/) |  |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/imathbox/as_argument_of_function/#MathFunctionsOfTwoArguments-IMathElement/) |  |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/imathbox/as_argument_of_function/#MathFunctionsOfTwoArguments-string/) |  |
| [set_subscript](/slides/python-net/aspose.slides.mathtext/imathbox/set_subscript/#IMathElement/) |  |
| [set_subscript](/slides/python-net/aspose.slides.mathtext/imathbox/set_subscript/#string/) |  |
| [set_superscript](/slides/python-net/aspose.slides.mathtext/imathbox/set_superscript/#IMathElement/) |  |
| [set_superscript](/slides/python-net/aspose.slides.mathtext/imathbox/set_superscript/#string/) |  |
| [set_sub_superscript_on_the_right](/slides/python-net/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#IMathElement-IMathElement/) |  |
| [set_sub_superscript_on_the_right](/slides/python-net/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#string-string/) |  |
| [set_sub_superscript_on_the_left](/slides/python-net/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#IMathElement-IMathElement/) |  |
| [set_sub_superscript_on_the_left](/slides/python-net/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#string-string/) |  |
| [radical](/slides/python-net/aspose.slides.mathtext/imathbox/radical/#IMathElement/) |  |
| [radical](/slides/python-net/aspose.slides.mathtext/imathbox/radical/#string/) |  |
| [set_upper_limit](/slides/python-net/aspose.slides.mathtext/imathbox/set_upper_limit/#IMathElement/) |  |
| [set_upper_limit](/slides/python-net/aspose.slides.mathtext/imathbox/set_upper_limit/#string/) |  |
| [set_lower_limit](/slides/python-net/aspose.slides.mathtext/imathbox/set_lower_limit/#IMathElement/) |  |
| [set_lower_limit](/slides/python-net/aspose.slides.mathtext/imathbox/set_lower_limit/#string/) |  |
| [nary](/slides/python-net/aspose.slides.mathtext/imathbox/nary/#MathNaryOperatorTypes-IMathElement-IMathElement/) |  |
| [nary](/slides/python-net/aspose.slides.mathtext/imathbox/nary/#MathNaryOperatorTypes-string-string/) |  |
| [integral](/slides/python-net/aspose.slides.mathtext/imathbox/integral/#MathIntegralTypes-IMathElement-IMathElement-MathLimitLocations/) |  |
| [integral](/slides/python-net/aspose.slides.mathtext/imathbox/integral/#MathIntegralTypes-IMathElement-IMathElement/) |  |
| [integral](/slides/python-net/aspose.slides.mathtext/imathbox/integral/#MathIntegralTypes/) |  |
| [integral](/slides/python-net/aspose.slides.mathtext/imathbox/integral/#MathIntegralTypes-string-string-MathLimitLocations/) |  |
| [integral](/slides/python-net/aspose.slides.mathtext/imathbox/integral/#MathIntegralTypes-string-string/) |  |
| [group](/slides/python-net/aspose.slides.mathtext/imathbox/group/#/) |  |
| [group](/slides/python-net/aspose.slides.mathtext/imathbox/group/#char-MathTopBotPositions-MathTopBotPositions/) |  |
| [to_border_box](/slides/python-net/aspose.slides.mathtext/imathbox/to_border_box/#/) |  |
| [to_border_box](/slides/python-net/aspose.slides.mathtext/imathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool/) |  |
| [get_children](/slides/python-net/aspose.slides.mathtext/imathbox/get_children/#/) |  |
| [to_math_array](/slides/python-net/aspose.slides.mathtext/imathbox/to_math_array/#/) |  |
| [accent](/slides/python-net/aspose.slides.mathtext/imathbox/accent/#char/) |  |
| [overbar](/slides/python-net/aspose.slides.mathtext/imathbox/overbar/#/) |  |
| [underbar](/slides/python-net/aspose.slides.mathtext/imathbox/underbar/#/) |  |
| [to_box](/slides/python-net/aspose.slides.mathtext/imathbox/to_box/#/) |  |

