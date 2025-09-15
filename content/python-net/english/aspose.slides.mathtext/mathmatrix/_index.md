---
title: MathMatrix class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/mathmatrix/
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
| [`__init__`](/slides/python-net/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | Initializes a new instance of the MathMatrix class. |

## Properties

| Property | Description |
| :- | :- |
| [`row_count`](/slides/python-net/aspose.slides.mathtext/mathmatrix/row_count/) | Number of rows in the matrix |
| [`column_count`](/slides/python-net/aspose.slides.mathtext/mathmatrix/column_count/) | Number of columns in the matrix |
| [`hide_placeholders`](/slides/python-net/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | Hide the placeholders for empty matrix elements<br/>            Default: false |
| [`base_justification`](/slides/python-net/aspose.slides.mathtext/mathmatrix/base_justification/) | Specifies the vertical justification respect to surrounding text. <br/>            Possible values are top, bottom, and center.<br/>            Default: Center |
| [`min_column_width`](/slides/python-net/aspose.slides.mathtext/mathmatrix/min_column_width/) | Minimum column width in twips (1/20th of a point)<br/>            The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to <br/>            the MinColumnWidth to determine the total Matrix Column Spacing<br/>            (distance between the same edges of different columns).<br/>            Default: 0. |
| [`column_gap_rule`](/slides/python-net/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | The type of horizontal spacing between columns of a matrix; <br/>            Horizontal spacing units can be ems or points (stored as twips).<br/>            Default: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/aspose.slides.mathtext/mathmatrix/column_gap/) | The value of horizontal spacing between columns of a matrix;<br/>            If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)<br/>            If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments.<br/>            In other cases ignored.<br/>            Default: 0 |
| [`row_gap_rule`](/slides/python-net/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | The type of vertical spacing between rows of a matrix; <br/>            Vertical spacing units can be lines or points (stored as twips).<br/>            Default: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/aspose.slides.mathtext/mathmatrix/row_gap/) | The value of vertical spacing between rows of a matrix;<br/>            If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)<br/>            If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines.<br/>            Default: 0 |

## Methods

| Method | Description |
| :- | :- |
| [`join`](/slides/python-net/aspose.slides.mathtext/mathmatrix/join/#imathelement) | Joins a mathematical element and forms a mathematical block |
| [`join`](/slides/python-net/aspose.slides.mathtext/mathmatrix/join/#str) | Joins a mathematical text and forms a mathematical block |
| [`divide`](/slides/python-net/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | Creates a fraction with this numerator and specified denominator |
| [`divide`](/slides/python-net/aspose.slides.mathtext/mathmatrix/divide/#str) | Creates a fraction with this numerator and specified denominator |
| [`divide`](/slides/python-net/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [`divide`](/slides/python-net/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [`enclose`](/slides/python-net/aspose.slides.mathtext/mathmatrix/enclose/#) | Encloses a math element in parenthesis |
| [`enclose`](/slides/python-net/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [`function`](/slides/python-net/aspose.slides.mathtext/mathmatrix/function/#imathelement) | Takes a function of an argument using this instance as the function name |
| [`function`](/slides/python-net/aspose.slides.mathtext/mathmatrix/function/#str) | Takes a function of an argument using this instance as the function name |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | Takes specified function using this instance as the argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | Takes specified function using this instance as the argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | Takes specified function using this instance as the argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Takes specified function using this instance as the argument and specified additional argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Takes specified function using this instance as the argument and specified additional argument |
| [`set_subscript`](/slides/python-net/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | Creates subscript |
| [`set_subscript`](/slides/python-net/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | Creates subscript |
| [`set_superscript`](/slides/python-net/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | Creates superscript |
| [`set_superscript`](/slides/python-net/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | Creates superscript |
| [`set_sub_superscript_on_the_right`](/slides/python-net/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | Creates subscript and superscript on the right |
| [`set_sub_superscript_on_the_right`](/slides/python-net/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | Creates subscript and superscript on the right |
| [`set_sub_superscript_on_the_left`](/slides/python-net/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | Creates subscript and superscript on the left |
| [`set_sub_superscript_on_the_left`](/slides/python-net/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | Creates subscript and superscript on the left |
| [`radical`](/slides/python-net/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | Specifies the mathematical root of the given degree from the specified argument. |
| [`radical`](/slides/python-net/aspose.slides.mathtext/mathmatrix/radical/#str) | Specifies the mathematical root of the given degree from the specified argument. |
| [`set_upper_limit`](/slides/python-net/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | Takes upper limit |
| [`set_upper_limit`](/slides/python-net/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | Takes upper limit |
| [`set_lower_limit`](/slides/python-net/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | Takes lower limit |
| [`set_lower_limit`](/slides/python-net/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | Takes lower limit |
| [`nary`](/slides/python-net/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | Creates a N-ary operator |
| [`nary`](/slides/python-net/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | Creates a N-ary operator |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Takes the integral |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | Takes the integral |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | Takes the integral without limits |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | Takes the integral |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | Takes the integral |
| [`group`](/slides/python-net/aspose.slides.mathtext/mathmatrix/group/#) | Places this element in a group using a bottom curly bracket |
| [`group`](/slides/python-net/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [`to_border_box`](/slides/python-net/aspose.slides.mathtext/mathmatrix/to_border_box/#) | Places this element in a border-box |
| [`to_border_box`](/slides/python-net/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Places this element in a border-box |
| [`to_math_array`](/slides/python-net/aspose.slides.mathtext/mathmatrix/to_math_array/#) | Puts in a vertical array |
| [`accent`](/slides/python-net/aspose.slides.mathtext/mathmatrix/accent/#char) | Sets an accent mark (a character on the top of this element) |
| [`overbar`](/slides/python-net/aspose.slides.mathtext/mathmatrix/overbar/#) | Sets a bar on the top of this element |
| [`underbar`](/slides/python-net/aspose.slides.mathtext/mathmatrix/underbar/#) | Sets a bar on the bottom of this element |
| [`to_box`](/slides/python-net/aspose.slides.mathtext/mathmatrix/to_box/#) | Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within. |
| [`get_column_alignment`](/slides/python-net/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | Get the horizontal alignment of the specified column |
| [`set_column_alignment`](/slides/python-net/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Set the horizontal alignment of the specified column |
| [`set_columns_alignment`](/slides/python-net/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Set the horizontal alignment of the specified columns |
| [`insert_row_before`](/slides/python-net/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | Insert a new row before the specified one<br/>            Initially all elements in the new row are None. |
| [`insert_row_after`](/slides/python-net/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | Insert a new row after the specified one<br/>            Initially all elements in the new row are None. |
| [`delete_row`](/slides/python-net/aspose.slides.mathtext/mathmatrix/delete_row/#int) | Deletes the specified row |
| [`insert_column_before`](/slides/python-net/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | Insert a new column before the specified one<br/>            Initially all elements in the new column are None. |
| [`insert_column_after`](/slides/python-net/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | Insert a new column after the specified one<br/>            Initially all elements in the new column are None. |
| [`delete_column`](/slides/python-net/aspose.slides.mathtext/mathmatrix/delete_column/#int) | Deletes the specified column |
| [`get_children`](/slides/python-net/aspose.slides.mathtext/mathmatrix/get_children/#) | Get children elements |


### Examples

Example:


### See Also
* class [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)
* class [`MathMatrix`](/slides/python-net/aspose.slides.mathtext/mathmatrix)
* module [`aspose.slides.mathtext`](/slides/python-net/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)

