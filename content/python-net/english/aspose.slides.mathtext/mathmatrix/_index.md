---
title: MathMatrix
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/mathmatrix/
---


MathMatrix class

Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. 
            It is important to note that matrices do not have built in delimiters. 
            To place the matrix in the brackets you should use the delimiter object (IMathDelimiter).
            Null arguments can be used to create gaps in matrices.

**Inheritance:**[`MathMatrix`](/slides/python-net/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)

The MathMatrix type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#int-int/) | Initializes a new instance of the MathMatrix class. |

## Properties

| Property | Description |
| :- | :- |
| [row_count](/slides/python-net/aspose.slides.mathtext/mathmatrix/row_count/) | Number of rows in the matrix |
| [column_count](/slides/python-net/aspose.slides.mathtext/mathmatrix/column_count/) | Number of columns in the matrix |
| [hide_placeholders](/slides/python-net/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | Hide the placeholders for empty matrix elements<br/>            Default: false |
| [base_justification](/slides/python-net/aspose.slides.mathtext/mathmatrix/base_justification/) | Specifies the vertical justification respect to surrounding text. <br/>            Possible values are top, bottom, and center.<br/>            Default: Center |
| [min_column_width](/slides/python-net/aspose.slides.mathtext/mathmatrix/min_column_width/) | Minimum column width in twips (1/20th of a point)<br/>            The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to <br/>            the MinColumnWidth to determine the total Matrix Column Spacing<br/>            (distance between the same edges of different columns).<br/>            Default: 0. |
| [column_gap_rule](/slides/python-net/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | The type of horizontal spacing between columns of a matrix; <br/>            Horizontal spacing units can be ems or points (stored as twips).<br/>            Default: SingleSpacingGap (0) |
| [column_gap](/slides/python-net/aspose.slides.mathtext/mathmatrix/column_gap/) | The value of horizontal spacing between columns of a matrix;<br/>            If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)<br/>            If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments.<br/>            In other cases ignored.<br/>            Default: 0 |
| [row_gap_rule](/slides/python-net/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | The type of vertical spacing between rows of a matrix; <br/>            Vertical spacing units can be lines or points (stored as twips).<br/>            Default: SingleSpacingGap (0) |
| [row_gap](/slides/python-net/aspose.slides.mathtext/mathmatrix/row_gap/) | The value of vertical spacing between rows of a matrix;<br/>            If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)<br/>            If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines.<br/>            Default: 0 |
| [as_i_math_element](/slides/python-net/aspose.slides.mathtext/mathmatrix/as_i_math_element/) |  |

## Methods

| Method | Description |
| :- | :- |
| [join](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#IMathElement/) | Joins a mathematical element and forms a mathematical block |
| [join](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#string/) | Joins a mathematical text and forms a mathematical block |
| [divide](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#IMathElement/) | Creates a fraction with this numerator and specified denominator |
| [divide](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#string/) | Creates a fraction with this numerator and specified denominator |
| [divide](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#IMathElement-MathFractionTypes/) | Creates a fraction of the specified type with this numerator and specified denominator |
| [divide](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#string-MathFractionTypes/) | Creates a fraction of the specified type with this numerator and specified denominator |
| [enclose](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#/) | Encloses a math element in parenthesis |
| [enclose](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#char-char/) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [function](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#IMathElement/) | Takes a function of an argument using this instance as the function name |
| [function](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#string/) | Takes a function of an argument using this instance as the function name |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#IMathElement/) | Takes specified function using this instance as the argument |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#string/) | Takes specified function using this instance as the argument |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#MathFunctionsOfOneArgument/) | Takes specified function using this instance as the argument |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#MathFunctionsOfTwoArguments-IMathElement/) | Takes specified function using this instance as the argument and specified additional argument |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#MathFunctionsOfTwoArguments-string/) | Takes specified function using this instance as the argument and specified additional argument |
| [set_subscript](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#IMathElement/) | Creates subscript |
| [set_subscript](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#string/) | Creates subscript |
| [set_superscript](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#IMathElement/) | Creates superscript |
| [set_superscript](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#string/) | Creates superscript |
| [set_sub_superscript_on_the_right](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#IMathElement-IMathElement/) | Creates subscript and superscript on the right |
| [set_sub_superscript_on_the_right](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#string-string/) | Creates subscript and superscript on the right |
| [set_sub_superscript_on_the_left](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#IMathElement-IMathElement/) | Creates subscript and superscript on the left |
| [set_sub_superscript_on_the_left](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#string-string/) | Creates subscript and superscript on the left |
| [radical](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#IMathElement/) | Specifies the mathematical root of the given degree from the specified argument. |
| [radical](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#string/) | Specifies the mathematical root of the given degree from the specified argument. |
| [set_upper_limit](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#IMathElement/) | Takes upper limit |
| [set_upper_limit](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#string/) | Takes upper limit |
| [set_lower_limit](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#IMathElement/) | Takes lower limit |
| [set_lower_limit](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#string/) | Takes lower limit |
| [nary](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#MathNaryOperatorTypes-IMathElement-IMathElement/) | Creates a N-ary operator |
| [nary](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#MathNaryOperatorTypes-string-string/) | Creates a N-ary operator |
| [integral](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#MathIntegralTypes-IMathElement-IMathElement-MathLimitLocations/) | Takes the integral |
| [integral](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#MathIntegralTypes-IMathElement-IMathElement/) | Takes the integral |
| [integral](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#MathIntegralTypes/) | Takes the integral without limits |
| [integral](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#MathIntegralTypes-string-string-MathLimitLocations/) | Takes the integral |
| [integral](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#MathIntegralTypes-string-string/) | Takes the integral |
| [group](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#/) | Places this element in a group using a bottom curly bracket |
| [group](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#char-MathTopBotPositions-MathTopBotPositions/) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [to_border_box](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#/) | Places this element in a border-box |
| [to_border_box](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#bool-bool-bool-bool-bool-bool-bool-bool/) | Places this element in a border-box |
| [to_math_array](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#/) | Puts in a vertical array |
| [accent](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#char/) | Sets an accent mark (a character on the top of this element) |
| [overbar](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#/) | Sets a bar on the top of this element |
| [underbar](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#/) | Sets a bar on the bottom of this element |
| [to_box](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#/) | Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within. |
| [get_column_alignment](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#int/) | Get the horizontal alignment of the specified column |
| [set_column_alignment](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#int-MathHorizontalAlignment/) | Set the horizontal alignment of the specified column |
| [set_columns_alignment](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#int-int-MathHorizontalAlignment/) | Set the horizontal alignment of the specified columns |
| [insert_row_before](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#int/) | Insert a new row before the specified one<br/>            Initially all elements in the new row are null. |
| [insert_row_after](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#int/) | Insert a new row after the specified one<br/>            Initially all elements in the new row are null. |
| [delete_row](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#int/) | Deletes the specified row |
| [insert_column_before](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#int/) | Insert a new column before the specified one<br/>            Initially all elements in the new column are null. |
| [insert_column_after](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#int/) | Insert a new column after the specified one<br/>            Initially all elements in the new column are null. |
| [delete_column](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#int/) | Deletes the specified column |
| [get_children](/slides/python-net/aspose.slides.mathtext/mathmatrix/mathmatrix/#/) | Get children elements |

