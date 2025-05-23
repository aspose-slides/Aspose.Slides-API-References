﻿---
title: IMathDelimiter class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/imathdelimiter/
---


## IMathDelimiter class

Specifies the delimiter object, consisting of opening and closing characters (such as parentheses, 
            braces, brackets, and vertical bars), and one or more mathematical elements inside, separated by a specified character.
            Examples: (𝑥2); [𝑥2|𝑦2]

The IMathDelimiter type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`arguments`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/arguments/) | One or more mathematical elements separated by delimiter characters |
| [`beginning_character`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/beginning_character/) | Delimiter Beginning Character specifies the beginning, or opening, delimiter character. <br/>            Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces.<br/>            The default value: '('. |
| [`separator_character`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/separator_character/) | Delimiter Separator Character specifies the character that separates arguments in the delimiter object. <br/>            The default: '\|'. |
| [`ending_character`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/ending_character/) | Delimiter Ending Character specifies the ending, or closing, delimiter character. <br/>            Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces.<br/>            The default: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/grow_to_match_operand_height/) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            When true, the delimiters grows vertically to match its operand height.<br/>            The default value is true |
| [`delimiter_shape`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/delimiter_shape/) | Specifies the shape of delimiters in the delimiter object. <br/>            When is MathDelimiterShape.Centered, delimiters are centered around the math axis of the mathematical text <br/>            and still be made to fit the entire height of their contents.<br/>            When is MathDelimiterShape.Match, their height and shape are altered to exactly match their contents. |

## Methods

| Method | Description |
| :- | :- |
| [`join`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/join/#imathelement) |  |
| [`join`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/join/#str) |  |
| [`divide`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/divide/#imathelement) |  |
| [`divide`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/divide/#str) |  |
| [`divide`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/divide/#imathelement-mathfractiontypes) |  |
| [`divide`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/divide/#str-mathfractiontypes) |  |
| [`enclose`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/enclose/#) |  |
| [`enclose`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/enclose/#char-char) |  |
| [`function`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/function/#imathelement) |  |
| [`function`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/function/#str) |  |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#str) |  |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_subscript/#imathelement) |  |
| [`set_subscript`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_subscript/#str) |  |
| [`set_superscript`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_superscript/#imathelement) |  |
| [`set_superscript`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/radical/#imathelement) |  |
| [`radical`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/radical/#str) |  |
| [`set_upper_limit`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_upper_limit/#imathelement) |  |
| [`set_upper_limit`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_upper_limit/#str) |  |
| [`set_lower_limit`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_lower_limit/#imathelement) |  |
| [`set_lower_limit`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/set_lower_limit/#str) |  |
| [`nary`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes) |  |
| [`integral`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-str-str) |  |
| [`group`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/group/#) |  |
| [`group`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/to_border_box/#) |  |
| [`to_border_box`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`delimit`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/delimit/#char) | Delimits arguments using the specified delimiter character |
| [`get_children`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/get_children/#) |  |
| [`to_math_array`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/to_math_array/#) |  |
| [`accent`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/accent/#char) |  |
| [`overbar`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/overbar/#) |  |
| [`underbar`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/underbar/#) |  |
| [`to_box`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/to_box/#) |  |


### Examples

Example:


### See Also
* module [`aspose.slides.mathtext`](/slides/python-net/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)

