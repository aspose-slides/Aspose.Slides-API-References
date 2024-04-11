---
title: MathDelimiter class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/mathdelimiter/
---


## MathDelimiter class

Specifies the delimiter object, consisting of opening and closing characters (such as parentheses, 
            braces, brackets, and vertical bars), and one or more mathematical elements inside, separated by a specified character.
            Examples: (𝑥2); [𝑥2|𝑦2]

**Inheritance:**[`MathDelimiter`](/slides/python-net/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)

The MathDelimiter type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Initializes MathDelimiter with the specified element as single base argument |

## Properties

| Property | Description |
| :- | :- |
| [arguments](/slides/python-net/aspose.slides.mathtext/mathdelimiter/arguments/) | One or more mathematical elements separated by delimiter characters |
| [beginning_character](/slides/python-net/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character specifies the beginning, or opening, delimiter character. <br/>            Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces.<br/>            The default: '('. |
| [separator_character](/slides/python-net/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character specifies the character that separates arguments in the delimiter object. <br/>            The default: '\|'. |
| [ending_character](/slides/python-net/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character specifies the ending, or closing, delimiter character. <br/>            Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces.<br/>            The default: ')'. |
| [grow_to_match_operand_height](/slides/python-net/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            When true, the delimiters grows vertically to match its operand height.<br/>            The default value is true |
| [delimiter_shape](/slides/python-net/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Specifies the shape of delimiters in the delimiter object. <br/>            When is MathDelimiterShape.Centered, delimiters are centered around the math axis of the mathematical text <br/>            and still be made to fit the entire height of their contents.<br/>            When is MathDelimiterShape.Match, their height and shape are altered to exactly match their contents. |
| [as_i_math_element](/slides/python-net/aspose.slides.mathtext/mathdelimiter/as_i_math_element/) |  |

## Methods

| Method | Description |
| :- | :- |
| [join](/slides/python-net/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Joins a mathematical element and forms a mathematical block |
| [join](/slides/python-net/aspose.slides.mathtext/mathdelimiter/join/#string) | Joins a mathematical text and forms a mathematical block |
| [divide](/slides/python-net/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Creates a fraction with this numerator and specified denominator |
| [divide](/slides/python-net/aspose.slides.mathtext/mathdelimiter/divide/#string) | Creates a fraction with this numerator and specified denominator |
| [divide](/slides/python-net/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [divide](/slides/python-net/aspose.slides.mathtext/mathdelimiter/divide/#string-mathfractiontypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [enclose](/slides/python-net/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [enclose](/slides/python-net/aspose.slides.mathtext/mathdelimiter/enclose/#) | Encloses a math element in parenthesis |
| [function](/slides/python-net/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Takes a function of an argument using this instance as the function name |
| [function](/slides/python-net/aspose.slides.mathtext/mathdelimiter/function/#string) | Takes a function of an argument using this instance as the function name |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Takes specified function using this instance as the argument |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#string) | Takes specified function using this instance as the argument |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Takes specified function using this instance as the argument |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Takes specified function using this instance as the argument and specified additional argument |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-string) | Takes specified function using this instance as the argument and specified additional argument |
| [set_subscript](/slides/python-net/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Creates subscript |
| [set_subscript](/slides/python-net/aspose.slides.mathtext/mathdelimiter/set_subscript/#string) | Creates subscript |
| [set_superscript](/slides/python-net/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Creates superscript |
| [set_superscript](/slides/python-net/aspose.slides.mathtext/mathdelimiter/set_superscript/#string) | Creates superscript |
| [set_sub_superscript_on_the_right](/slides/python-net/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Creates subscript and superscript on the right |
| [set_sub_superscript_on_the_right](/slides/python-net/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#string-string) | Creates subscript and superscript on the right |
| [set_sub_superscript_on_the_left](/slides/python-net/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Creates subscript and superscript on the left |
| [set_sub_superscript_on_the_left](/slides/python-net/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#string-string) | Creates subscript and superscript on the left |
| [radical](/slides/python-net/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Specifies the mathematical root of the given degree from the specified argument. |
| [radical](/slides/python-net/aspose.slides.mathtext/mathdelimiter/radical/#string) | Specifies the mathematical root of the given degree from the specified argument. |
| [set_upper_limit](/slides/python-net/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Takes upper limit |
| [set_upper_limit](/slides/python-net/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#string) | Takes upper limit |
| [set_lower_limit](/slides/python-net/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Takes lower limit |
| [set_lower_limit](/slides/python-net/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#string) | Takes lower limit |
| [nary](/slides/python-net/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Creates a N-ary operator |
| [nary](/slides/python-net/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-string-string) | Creates a N-ary operator |
| [integral](/slides/python-net/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Takes the integral |
| [integral](/slides/python-net/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Takes the integral |
| [integral](/slides/python-net/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Takes the integral without limits |
| [integral](/slides/python-net/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-string-string-mathlimitlocations) | Takes the integral |
| [integral](/slides/python-net/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-string-string) | Takes the integral |
| [group](/slides/python-net/aspose.slides.mathtext/mathdelimiter/group/#) | Places this element in a group using a bottom curly bracket |
| [group](/slides/python-net/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [to_border_box](/slides/python-net/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Places this element in a border-box |
| [to_border_box](/slides/python-net/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Places this element in a border-box |
| [to_math_array](/slides/python-net/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Puts in a vertical array |
| [accent](/slides/python-net/aspose.slides.mathtext/mathdelimiter/accent/#char) | Sets an accent mark (a character on the top of this element) |
| [overbar](/slides/python-net/aspose.slides.mathtext/mathdelimiter/overbar/#) | Sets a bar on the top of this element |
| [underbar](/slides/python-net/aspose.slides.mathtext/mathdelimiter/underbar/#) | Sets a bar on the bottom of this element |
| [to_box](/slides/python-net/aspose.slides.mathtext/mathdelimiter/to_box/#) | Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within. |
| [delimit](/slides/python-net/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Delimits arguments using the specified delimiter character |
| [get_children](/slides/python-net/aspose.slides.mathtext/mathdelimiter/get_children/#) | Get children elements |

