---
title: IMathMatrix
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/imathmatrix/
---


IMathMatrix class

Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. 
            It is important to note that matrices do not have built in delimiters. 
            To place the matrix in the brackets you should use the delimiter object (IMathDelimiter).
            Null arguments can be used to create gaps in matrices.

The IMathMatrix type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [row_count](/slides/python-net/aspose.slides.mathtext/imathmatrix/row_count/) | Number of rows in the matrix |
| [column_count](/slides/python-net/aspose.slides.mathtext/imathmatrix/column_count/) | Number of columns in the matrix |
| [hide_placeholders](/slides/python-net/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | Hide the placeholders for empty matrix elements<br/>            Default: false |
| [base_justification](/slides/python-net/aspose.slides.mathtext/imathmatrix/base_justification/) | Specifies the vertical justification respect to surrounding text. <br/>            Possible values are top, bottom, and center.<br/>            Default: Center |
| [min_column_width](/slides/python-net/aspose.slides.mathtext/imathmatrix/min_column_width/) | Minimum column width in twips (1/20th of a point)<br/>            The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to <br/>            the MinColumnWidth to determine the total Matrix Column Spacing<br/>            (distance between the same edges of different columns).<br/>            Default: 0. |
| [column_gap_rule](/slides/python-net/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | The type of horizontal spacing between columns of a matrix; <br/>            Horizontal spacing units can be ems or points (stored as twips).<br/>            Default: SingleSpacingGap (0) |
| [column_gap](/slides/python-net/aspose.slides.mathtext/imathmatrix/column_gap/) | The value of horizontal spacing between columns of a matrix;<br/>            If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)<br/>            If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments.<br/>            In other cases ignored.<br/>            Default: 0 |
| [row_gap_rule](/slides/python-net/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | The type of vertical spacing between rows of a matrix; <br/>            Vertical spacing units can be lines or points (stored as twips).<br/>            Default: SingleSpacingGap (0) |
| [row_gap](/slides/python-net/aspose.slides.mathtext/imathmatrix/row_gap/) | The value of vertical spacing between rows of a matrix;<br/>            If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)<br/>            If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines.<br/>            Default: 0 |
| [as_i_math_element](/slides/python-net/aspose.slides.mathtext/imathmatrix/as_i_math_element/) | Allows to get base IMathElement interface<br/>            <br/>[`IMathElement`](/slides/python-net/aspose.slides.mathtext/imathelement) |

## Methods

| Method | Description |
| :- | :- |
| [join](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#IMathElement/) |  |
| [join](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#string/) |  |
| [divide](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#IMathElement/) |  |
| [divide](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#string/) |  |
| [divide](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#IMathElement-MathFractionTypes/) |  |
| [divide](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#string-MathFractionTypes/) |  |
| [enclose](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#/) |  |
| [enclose](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#char-char/) |  |
| [function](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#IMathElement/) |  |
| [function](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#string/) |  |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#IMathElement/) |  |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#string/) |  |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#MathFunctionsOfOneArgument/) |  |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#MathFunctionsOfTwoArguments-IMathElement/) |  |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#MathFunctionsOfTwoArguments-string/) |  |
| [set_subscript](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#IMathElement/) |  |
| [set_subscript](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#string/) |  |
| [set_superscript](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#IMathElement/) |  |
| [set_superscript](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#string/) |  |
| [set_sub_superscript_on_the_right](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#IMathElement-IMathElement/) |  |
| [set_sub_superscript_on_the_right](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#string-string/) |  |
| [set_sub_superscript_on_the_left](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#IMathElement-IMathElement/) |  |
| [set_sub_superscript_on_the_left](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#string-string/) |  |
| [radical](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#IMathElement/) |  |
| [radical](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#string/) |  |
| [set_upper_limit](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#IMathElement/) |  |
| [set_upper_limit](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#string/) |  |
| [set_lower_limit](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#IMathElement/) |  |
| [set_lower_limit](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#string/) |  |
| [nary](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#MathNaryOperatorTypes-IMathElement-IMathElement/) |  |
| [nary](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#MathNaryOperatorTypes-string-string/) |  |
| [integral](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#MathIntegralTypes-IMathElement-IMathElement-MathLimitLocations/) |  |
| [integral](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#MathIntegralTypes-IMathElement-IMathElement/) |  |
| [integral](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#MathIntegralTypes/) |  |
| [integral](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#MathIntegralTypes-string-string-MathLimitLocations/) |  |
| [integral](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#MathIntegralTypes-string-string/) |  |
| [group](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#/) |  |
| [group](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#char-MathTopBotPositions-MathTopBotPositions/) |  |
| [to_border_box](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#/) |  |
| [to_border_box](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#bool-bool-bool-bool-bool-bool-bool-bool/) |  |
| [get_column_alignment](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#int/) | Get the horizontal alignment of the specified column |
| [set_column_alignment](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#int-MathHorizontalAlignment/) | Set the horizontal alignment of the specified column |
| [set_columns_alignment](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#int-int-MathHorizontalAlignment/) | Set the horizontal alignment of the specified columns |
| [insert_row_before](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#int/) | Insert a new row before the specified one<br/>            Initially all elements in the new row are null. |
| [insert_row_after](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#int/) | Insert a new row after the specified one<br/>            Initially all elements in the new row are null. |
| [delete_row](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#int/) | Deletes the specified row |
| [insert_column_before](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#int/) | Insert a new column before the specified one<br/>            Initially all elements in the new column are null. |
| [insert_column_after](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#int/) | Insert a new column after the specified one<br/>            Initially all elements in the new column are null. |
| [delete_column](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#int/) | Deletes the specified column |
| [get_children](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#/) |  |
| [to_math_array](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#/) |  |
| [accent](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#char/) |  |
| [overbar](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#/) |  |
| [underbar](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#/) |  |
| [to_box](/slides/python-net/aspose.slides.mathtext/imathmatrix/imathmatrix/#/) |  |

