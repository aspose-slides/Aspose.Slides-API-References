---
title: MathMatrix class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/
---


## MathMatrix class

Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. 
            It is important to note that matrices do not have built in delimiters. 
            To place the matrix in the brackets you should use the delimiter object (IMathDelimiter).
            Null arguments can be used to create gaps in matrices.

**Inheritance:**[`MathMatrix`](/slides/python-net/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)

The MathMatrix type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#int-int) | Initializes a new instance of the MathMatrix class. |

## Properties

| Property | Description |
| :- | :- |
| [row_count](/slides/python-net/aspose.slides.mathtext/row_count) | Number of rows in the matrix |
| [column_count](/slides/python-net/aspose.slides.mathtext/column_count) | Number of columns in the matrix |
| [hide_placeholders](/slides/python-net/aspose.slides.mathtext/hide_placeholders) | Hide the placeholders for empty matrix elements<br/>            Default: false |
| [base_justification](/slides/python-net/aspose.slides.mathtext/base_justification) | Specifies the vertical justification respect to surrounding text. <br/>            Possible values are top, bottom, and center.<br/>            Default: Center |
| [min_column_width](/slides/python-net/aspose.slides.mathtext/min_column_width) | Minimum column width in twips (1/20th of a point)<br/>            The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to <br/>            the MinColumnWidth to determine the total Matrix Column Spacing<br/>            (distance between the same edges of different columns).<br/>            Default: 0. |
| [column_gap_rule](/slides/python-net/aspose.slides.mathtext/column_gap_rule) | The type of horizontal spacing between columns of a matrix; <br/>            Horizontal spacing units can be ems or points (stored as twips).<br/>            Default: SingleSpacingGap (0) |
| [column_gap](/slides/python-net/aspose.slides.mathtext/column_gap) | The value of horizontal spacing between columns of a matrix;<br/>            If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)<br/>            If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments.<br/>            In other cases ignored.<br/>            Default: 0 |
| [row_gap_rule](/slides/python-net/aspose.slides.mathtext/row_gap_rule) | The type of vertical spacing between rows of a matrix; <br/>            Vertical spacing units can be lines or points (stored as twips).<br/>            Default: SingleSpacingGap (0) |
| [row_gap](/slides/python-net/aspose.slides.mathtext/row_gap) | The value of vertical spacing between rows of a matrix;<br/>            If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)<br/>            If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines.<br/>            Default: 0 |
| [as_i_math_element](/slides/python-net/aspose.slides.mathtext/as_i_math_element) |  |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#IMathElement) | Joins a mathematical element and forms a mathematical block |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#string) | Joins a mathematical text and forms a mathematical block |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#IMathElement) | Creates a fraction with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#string) | Creates a fraction with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#IMathElement-MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#string-MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#) | Encloses a math element in parenthesis |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#char-char) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#IMathElement) | Takes a function of an argument using this instance as the function name |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#string) | Takes a function of an argument using this instance as the function name |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#IMathElement) | Takes specified function using this instance as the argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#string) | Takes specified function using this instance as the argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#MathFunctionsOfOneArgument) | Takes specified function using this instance as the argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#MathFunctionsOfTwoArguments-IMathElement) | Takes specified function using this instance as the argument and specified additional argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#MathFunctionsOfTwoArguments-string) | Takes specified function using this instance as the argument and specified additional argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#IMathElement) | Creates subscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#string) | Creates subscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#IMathElement) | Creates superscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#string) | Creates superscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#IMathElement-IMathElement) | Creates subscript and superscript on the right |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#string-string) | Creates subscript and superscript on the right |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#IMathElement-IMathElement) | Creates subscript and superscript on the left |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#string-string) | Creates subscript and superscript on the left |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#IMathElement) | Specifies the mathematical root of the given degree from the specified argument. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#string) | Specifies the mathematical root of the given degree from the specified argument. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#IMathElement) | Takes upper limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#string) | Takes upper limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#IMathElement) | Takes lower limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#string) | Takes lower limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#MathNaryOperatorTypes-IMathElement-IMathElement) | Creates a N-ary operator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#MathNaryOperatorTypes-string-string) | Creates a N-ary operator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#MathIntegralTypes-IMathElement-IMathElement-MathLimitLocations) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#MathIntegralTypes-IMathElement-IMathElement) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#MathIntegralTypes) | Takes the integral without limits |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#MathIntegralTypes-string-string-MathLimitLocations) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#MathIntegralTypes-string-string) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#) | Places this element in a group using a bottom curly bracket |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#char-MathTopBotPositions-MathTopBotPositions) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#) | Places this element in a border-box |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#bool-bool-bool-bool-bool-bool-bool-bool) | Places this element in a border-box |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#) | Puts in a vertical array |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#char) | Sets an accent mark (a character on the top of this element) |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#) | Sets a bar on the top of this element |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#) | Sets a bar on the bottom of this element |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#) | Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#int) | Get the horizontal alignment of the specified column |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#int-MathHorizontalAlignment) | Set the horizontal alignment of the specified column |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#int-int-MathHorizontalAlignment) | Set the horizontal alignment of the specified columns |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#int) | Insert a new row before the specified one<br/>            Initially all elements in the new row are null. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#int) | Insert a new row after the specified one<br/>            Initially all elements in the new row are null. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#int) | Deletes the specified row |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#int) | Insert a new column before the specified one<br/>            Initially all elements in the new column are null. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#int) | Insert a new column after the specified one<br/>            Initially all elements in the new column are null. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#int) | Deletes the specified column |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/#) | Get children elements |

