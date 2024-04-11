---
title: IMathDelimiter
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/imathdelimiter/
---


IMathDelimiter class

Specifies the delimiter object, consisting of opening and closing characters (such as parentheses, 
            braces, brackets, and vertical bars), and one or more mathematical elements inside, separated by a specified character.
            Examples: (𝑥2); [𝑥2|𝑦2]

The IMathDelimiter type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [arguments](/slides/python-net/aspose.slides.mathtext/imathdelimiter/arguments/) | One or more mathematical elements separated by delimiter characters |
| [beginning_character](/slides/python-net/aspose.slides.mathtext/imathdelimiter/beginning_character/) | Delimiter Beginning Character specifies the beginning, or opening, delimiter character. <br/>            Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces.<br/>            The default value: '('. |
| [separator_character](/slides/python-net/aspose.slides.mathtext/imathdelimiter/separator_character/) | Delimiter Separator Character specifies the character that separates arguments in the delimiter object. <br/>            The default: '\|'. |
| [ending_character](/slides/python-net/aspose.slides.mathtext/imathdelimiter/ending_character/) | Delimiter Ending Character specifies the ending, or closing, delimiter character. <br/>            Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces.<br/>            The default: ')'. |
| [grow_to_match_operand_height](/slides/python-net/aspose.slides.mathtext/imathdelimiter/grow_to_match_operand_height/) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            When true, the delimiters grows vertically to match its operand height.<br/>            The default value is true |
| [delimiter_shape](/slides/python-net/aspose.slides.mathtext/imathdelimiter/delimiter_shape/) | Specifies the shape of delimiters in the delimiter object. <br/>            When is MathDelimiterShape.Centered, delimiters are centered around the math axis of the mathematical text <br/>            and still be made to fit the entire height of their contents.<br/>            When is MathDelimiterShape.Match, their height and shape are altered to exactly match their contents. |
| [as_i_math_element](/slides/python-net/aspose.slides.mathtext/imathdelimiter/as_i_math_element/) | Allows to get base IMathElement interface<br/>            [`IMathElement`](/slides/python-net/aspose.slides.mathtext/imathelement) |

## Methods

| Method | Description |
| :- | :- |
| [join](/slides/python-net/aspose.slides.mathtext/imathdelimiter/join/#IMathElement) |  |
| [join](/slides/python-net/aspose.slides.mathtext/imathdelimiter/join/#string) |  |
| [divide](/slides/python-net/aspose.slides.mathtext/imathdelimiter/divide/#IMathElement) |  |
| [divide](/slides/python-net/aspose.slides.mathtext/imathdelimiter/divide/#string) |  |
| [divide](/slides/python-net/aspose.slides.mathtext/imathdelimiter/divide/#IMathElement-MathFractionTypes) |  |
| [divide](/slides/python-net/aspose.slides.mathtext/imathdelimiter/divide/#string-MathFractionTypes) |  |
| [enclose](/slides/python-net/aspose.slides.mathtext/imathdelimiter/enclose/#) |  |
| [enclose](/slides/python-net/aspose.slides.mathtext/imathdelimiter/enclose/#char-char) |  |
| [function](/slides/python-net/aspose.slides.mathtext/imathdelimiter/function/#IMathElement) |  |
| [function](/slides/python-net/aspose.slides.mathtext/imathdelimiter/function/#string) |  |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#IMathElement) |  |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#string) |  |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#MathFunctionsOfOneArgument) |  |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#MathFunctionsOfTwoArguments-IMathElement) |  |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#MathFunctionsOfTwoArguments-string) |  |
| [set_subscript](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_subscript/#IMathElement) |  |
| [set_subscript](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_subscript/#string) |  |
| [set_superscript](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_superscript/#IMathElement) |  |
| [set_superscript](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_superscript/#string) |  |
| [set_sub_superscript_on_the_right](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_right/#IMathElement-IMathElement) |  |
| [set_sub_superscript_on_the_right](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_right/#string-string) |  |
| [set_sub_superscript_on_the_left](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_left/#IMathElement-IMathElement) |  |
| [set_sub_superscript_on_the_left](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_left/#string-string) |  |
| [radical](/slides/python-net/aspose.slides.mathtext/imathdelimiter/radical/#IMathElement) |  |
| [radical](/slides/python-net/aspose.slides.mathtext/imathdelimiter/radical/#string) |  |
| [set_upper_limit](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_upper_limit/#IMathElement) |  |
| [set_upper_limit](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_upper_limit/#string) |  |
| [set_lower_limit](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_lower_limit/#IMathElement) |  |
| [set_lower_limit](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_lower_limit/#string) |  |
| [nary](/slides/python-net/aspose.slides.mathtext/imathdelimiter/nary/#MathNaryOperatorTypes-IMathElement-IMathElement) |  |
| [nary](/slides/python-net/aspose.slides.mathtext/imathdelimiter/nary/#MathNaryOperatorTypes-string-string) |  |
| [integral](/slides/python-net/aspose.slides.mathtext/imathdelimiter/integral/#MathIntegralTypes-IMathElement-IMathElement-MathLimitLocations) |  |
| [integral](/slides/python-net/aspose.slides.mathtext/imathdelimiter/integral/#MathIntegralTypes-IMathElement-IMathElement) |  |
| [integral](/slides/python-net/aspose.slides.mathtext/imathdelimiter/integral/#MathIntegralTypes) |  |
| [integral](/slides/python-net/aspose.slides.mathtext/imathdelimiter/integral/#MathIntegralTypes-string-string-MathLimitLocations) |  |
| [integral](/slides/python-net/aspose.slides.mathtext/imathdelimiter/integral/#MathIntegralTypes-string-string) |  |
| [group](/slides/python-net/aspose.slides.mathtext/imathdelimiter/group/#) |  |
| [group](/slides/python-net/aspose.slides.mathtext/imathdelimiter/group/#char-MathTopBotPositions-MathTopBotPositions) |  |
| [to_border_box](/slides/python-net/aspose.slides.mathtext/imathdelimiter/to_border_box/#) |  |
| [to_border_box](/slides/python-net/aspose.slides.mathtext/imathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [delimit](/slides/python-net/aspose.slides.mathtext/imathdelimiter/delimit/#char) | Delimits arguments using the specified delimiter character |
| [get_children](/slides/python-net/aspose.slides.mathtext/imathdelimiter/get_children/#) |  |
| [to_math_array](/slides/python-net/aspose.slides.mathtext/imathdelimiter/to_math_array/#) |  |
| [accent](/slides/python-net/aspose.slides.mathtext/imathdelimiter/accent/#char) |  |
| [overbar](/slides/python-net/aspose.slides.mathtext/imathdelimiter/overbar/#) |  |
| [underbar](/slides/python-net/aspose.slides.mathtext/imathdelimiter/underbar/#) |  |
| [to_box](/slides/python-net/aspose.slides.mathtext/imathdelimiter/to_box/#) |  |

