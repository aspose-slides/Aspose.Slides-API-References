---
title: MathDelimiter class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/
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
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#IMathElement) | Initializes MathDelimiter with the specified element as single base argument |

## Properties

| Property | Description |
| :- | :- |
| [arguments](/slides/python-net/aspose.slides.mathtext/arguments) | One or more mathematical elements separated by delimiter characters |
| [beginning_character](/slides/python-net/aspose.slides.mathtext/beginning_character) | Delimiter Beginning Character specifies the beginning, or opening, delimiter character. <br/>            Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces.<br/>            The default: '('. |
| [separator_character](/slides/python-net/aspose.slides.mathtext/separator_character) | Delimiter Separator Character specifies the character that separates arguments in the delimiter object. <br/>            The default: '\|'. |
| [ending_character](/slides/python-net/aspose.slides.mathtext/ending_character) | Delimiter Ending Character specifies the ending, or closing, delimiter character. <br/>            Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces.<br/>            The default: ')'. |
| [grow_to_match_operand_height](/slides/python-net/aspose.slides.mathtext/grow_to_match_operand_height) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            When true, the delimiters grows vertically to match its operand height.<br/>            The default value is true |
| [delimiter_shape](/slides/python-net/aspose.slides.mathtext/delimiter_shape) | Specifies the shape of delimiters in the delimiter object. <br/>            When is MathDelimiterShape.Centered, delimiters are centered around the math axis of the mathematical text <br/>            and still be made to fit the entire height of their contents.<br/>            When is MathDelimiterShape.Match, their height and shape are altered to exactly match their contents. |
| [as_i_math_element](/slides/python-net/aspose.slides.mathtext/as_i_math_element) |  |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#IMathElement) | Joins a mathematical element and forms a mathematical block |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#string) | Joins a mathematical text and forms a mathematical block |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#IMathElement) | Creates a fraction with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#string) | Creates a fraction with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#IMathElement-MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#string-MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#char-char) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#) | Encloses a math element in parenthesis |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#IMathElement) | Takes a function of an argument using this instance as the function name |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#string) | Takes a function of an argument using this instance as the function name |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#IMathElement) | Takes specified function using this instance as the argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#string) | Takes specified function using this instance as the argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#MathFunctionsOfOneArgument) | Takes specified function using this instance as the argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#MathFunctionsOfTwoArguments-IMathElement) | Takes specified function using this instance as the argument and specified additional argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#MathFunctionsOfTwoArguments-string) | Takes specified function using this instance as the argument and specified additional argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#IMathElement) | Creates subscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#string) | Creates subscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#IMathElement) | Creates superscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#string) | Creates superscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#IMathElement-IMathElement) | Creates subscript and superscript on the right |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#string-string) | Creates subscript and superscript on the right |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#IMathElement-IMathElement) | Creates subscript and superscript on the left |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#string-string) | Creates subscript and superscript on the left |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#IMathElement) | Specifies the mathematical root of the given degree from the specified argument. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#string) | Specifies the mathematical root of the given degree from the specified argument. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#IMathElement) | Takes upper limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#string) | Takes upper limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#IMathElement) | Takes lower limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#string) | Takes lower limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#MathNaryOperatorTypes-IMathElement-IMathElement) | Creates a N-ary operator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#MathNaryOperatorTypes-string-string) | Creates a N-ary operator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#MathIntegralTypes-IMathElement-IMathElement-MathLimitLocations) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#MathIntegralTypes-IMathElement-IMathElement) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#MathIntegralTypes) | Takes the integral without limits |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#MathIntegralTypes-string-string-MathLimitLocations) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#MathIntegralTypes-string-string) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#) | Places this element in a group using a bottom curly bracket |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#char-MathTopBotPositions-MathTopBotPositions) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#) | Places this element in a border-box |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#bool-bool-bool-bool-bool-bool-bool-bool) | Places this element in a border-box |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#) | Puts in a vertical array |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#char) | Sets an accent mark (a character on the top of this element) |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#) | Sets a bar on the top of this element |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#) | Sets a bar on the bottom of this element |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#) | Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#char) | Delimits arguments using the specified delimiter character |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathdelimiter/#) | Get children elements |

