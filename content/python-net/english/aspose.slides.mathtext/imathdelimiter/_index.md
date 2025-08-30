---
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
| [`delimit`](/slides/python-net/aspose.slides.mathtext/imathdelimiter/delimit/#systemchar) | Delimits arguments using the specified delimiter character |


### Examples

Example:


### See Also
* module [`aspose.slides.mathtext`](/slides/python-net/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)

