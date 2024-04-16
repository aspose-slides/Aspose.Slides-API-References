---
title: IMathMatrix class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/imathmatrix/
---


## IMathMatrix class

Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. 
            It is important to note that matrices do not have built in delimiters. 
            To place the matrix in the brackets you should use the delimiter object (IMathDelimiter).
            Null arguments can be used to create gaps in matrices.

The IMathMatrix type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`row_count`](/slides/python-net/aspose.slides.mathtext/imathmatrix/row_count/) | Number of rows in the matrix |
| [`column_count`](/slides/python-net/aspose.slides.mathtext/imathmatrix/column_count/) | Number of columns in the matrix |
| [`hide_placeholders`](/slides/python-net/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | Hide the placeholders for empty matrix elements<br/>            Default: false |
| [`base_justification`](/slides/python-net/aspose.slides.mathtext/imathmatrix/base_justification/) | Specifies the vertical justification respect to surrounding text. <br/>            Possible values are top, bottom, and center.<br/>            Default: Center |
| [`min_column_width`](/slides/python-net/aspose.slides.mathtext/imathmatrix/min_column_width/) | Minimum column width in twips (1/20th of a point)<br/>            The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to <br/>            the MinColumnWidth to determine the total Matrix Column Spacing<br/>            (distance between the same edges of different columns).<br/>            Default: 0. |
| [`column_gap_rule`](/slides/python-net/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | The type of horizontal spacing between columns of a matrix; <br/>            Horizontal spacing units can be ems or points (stored as twips).<br/>            Default: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/aspose.slides.mathtext/imathmatrix/column_gap/) | The value of horizontal spacing between columns of a matrix;<br/>            If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)<br/>            If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments.<br/>            In other cases ignored.<br/>            Default: 0 |
| [`row_gap_rule`](/slides/python-net/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | The type of vertical spacing between rows of a matrix; <br/>            Vertical spacing units can be lines or points (stored as twips).<br/>            Default: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/aspose.slides.mathtext/imathmatrix/row_gap/) | The value of vertical spacing between rows of a matrix;<br/>            If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)<br/>            If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines.<br/>            Default: 0 |

## Methods

| Method | Description |
| :- | :- |
| [`join`](/slides/python-net/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join`](/slides/python-net/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide`](/slides/python-net/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide`](/slides/python-net/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide`](/slides/python-net/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide`](/slides/python-net/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose`](/slides/python-net/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose`](/slides/python-net/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function`](/slides/python-net/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function`](/slides/python-net/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript`](/slides/python-net/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript`](/slides/python-net/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript`](/slides/python-net/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript`](/slides/python-net/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right`](/slides/python-net/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right`](/slides/python-net/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left`](/slides/python-net/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left`](/slides/python-net/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical`](/slides/python-net/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical`](/slides/python-net/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit`](/slides/python-net/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit`](/slides/python-net/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit`](/slides/python-net/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit`](/slides/python-net/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary`](/slides/python-net/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary`](/slides/python-net/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral`](/slides/python-net/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral`](/slides/python-net/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral`](/slides/python-net/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral`](/slides/python-net/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral`](/slides/python-net/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group`](/slides/python-net/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group`](/slides/python-net/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box`](/slides/python-net/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box`](/slides/python-net/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment`](/slides/python-net/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | Get the horizontal alignment of the specified column |
| [`set_column_alignment`](/slides/python-net/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Set the horizontal alignment of the specified column |
| [`set_columns_alignment`](/slides/python-net/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Set the horizontal alignment of the specified columns |
| [`insert_row_before`](/slides/python-net/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | Insert a new row before the specified one<br/>            Initially all elements in the new row are null. |
| [`insert_row_after`](/slides/python-net/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | Insert a new row after the specified one<br/>            Initially all elements in the new row are null. |
| [`delete_row`](/slides/python-net/aspose.slides.mathtext/imathmatrix/delete_row/#int) | Deletes the specified row |
| [`insert_column_before`](/slides/python-net/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | Insert a new column before the specified one<br/>            Initially all elements in the new column are null. |
| [`insert_column_after`](/slides/python-net/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | Insert a new column after the specified one<br/>            Initially all elements in the new column are null. |
| [`delete_column`](/slides/python-net/aspose.slides.mathtext/imathmatrix/delete_column/#int) | Deletes the specified column |
| [`get_children`](/slides/python-net/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array`](/slides/python-net/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent`](/slides/python-net/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar`](/slides/python-net/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar`](/slides/python-net/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box`](/slides/python-net/aspose.slides.mathtext/imathmatrix/to_box/#) |  |


### See Also
* module [`aspose.slides.mathtext`](/slides/python-net/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)

