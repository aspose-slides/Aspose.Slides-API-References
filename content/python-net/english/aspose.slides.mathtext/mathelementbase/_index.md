---
title: MathElementBase
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/mathelementbase/
---


MathElementBase class

Base class for IMathElement with the implementation of some methods that are common to all inherited classes
            For internal use only. Inherited class must be IMathElement.

The MathElementBase type exposes the following members:

## Methods

| Method | Description |
| :- | :- |
| [join](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#IMathElement/) | Joins a mathematical element and forms a mathematical block |
| [join](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#string/) | Joins a mathematical text and forms a mathematical block |
| [divide](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#IMathElement/) | Creates a fraction with this numerator and specified denominator |
| [divide](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#string/) | Creates a fraction with this numerator and specified denominator |
| [divide](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#IMathElement-MathFractionTypes/) | Creates a fraction of the specified type with this numerator and specified denominator |
| [divide](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#string-MathFractionTypes/) | Creates a fraction of the specified type with this numerator and specified denominator |
| [enclose](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#/) | Encloses a math element in parenthesis |
| [enclose](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#char-char/) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [function](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#IMathElement/) | Takes a function of an argument using this instance as the function name |
| [function](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#string/) | Takes a function of an argument using this instance as the function name |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#IMathElement/) | Takes specified function using this instance as the argument |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#string/) | Takes specified function using this instance as the argument |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#MathFunctionsOfOneArgument/) | Takes specified function using this instance as the argument |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#MathFunctionsOfTwoArguments-IMathElement/) | Takes specified function using this instance as the argument and specified additional argument |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#MathFunctionsOfTwoArguments-string/) | Takes specified function using this instance as the argument and specified additional argument |
| [set_subscript](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#IMathElement/) | Creates subscript |
| [set_subscript](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#string/) | Creates subscript |
| [set_superscript](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#IMathElement/) | Creates superscript |
| [set_superscript](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#string/) | Creates superscript |
| [set_sub_superscript_on_the_right](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#IMathElement-IMathElement/) | Creates subscript and superscript on the right |
| [set_sub_superscript_on_the_right](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#string-string/) | Creates subscript and superscript on the right |
| [set_sub_superscript_on_the_left](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#IMathElement-IMathElement/) | Creates subscript and superscript on the left |
| [set_sub_superscript_on_the_left](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#string-string/) | Creates subscript and superscript on the left |
| [radical](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#IMathElement/) | Specifies the mathematical root of the given degree from the specified argument. |
| [radical](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#string/) | Specifies the mathematical root of the given degree from the specified argument. |
| [set_upper_limit](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#IMathElement/) | Takes upper limit |
| [set_upper_limit](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#string/) | Takes upper limit |
| [set_lower_limit](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#IMathElement/) | Takes lower limit |
| [set_lower_limit](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#string/) | Takes lower limit |
| [nary](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#MathNaryOperatorTypes-IMathElement-IMathElement/) | Creates a N-ary operator |
| [nary](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#MathNaryOperatorTypes-string-string/) | Creates a N-ary operator |
| [integral](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#MathIntegralTypes-IMathElement-IMathElement-MathLimitLocations/) | Takes the integral |
| [integral](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#MathIntegralTypes-IMathElement-IMathElement/) | Takes the integral |
| [integral](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#MathIntegralTypes/) | Takes the integral without limits |
| [integral](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#MathIntegralTypes-string-string-MathLimitLocations/) | Takes the integral |
| [integral](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#MathIntegralTypes-string-string/) | Takes the integral |
| [group](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#/) | Places this element in a group using a bottom curly bracket |
| [group](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#char-MathTopBotPositions-MathTopBotPositions/) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [to_border_box](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#/) | Places this element in a border-box |
| [to_border_box](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#bool-bool-bool-bool-bool-bool-bool-bool/) | Places this element in a border-box |
| [to_math_array](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#/) | Puts in a vertical array |
| [accent](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#char/) | Sets an accent mark (a character on the top of this element) |
| [overbar](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#/) | Sets a bar on the top of this element |
| [underbar](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#/) | Sets a bar on the bottom of this element |
| [to_box](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#/) | Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within. |
| [get_children](/slides/python-net/aspose.slides.mathtext/mathelementbase/mathelementbase/#/) |  |

