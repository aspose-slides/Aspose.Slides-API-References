---
title: IMathMatrix class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/
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
| [row_count](/slides/python-net/aspose.slides.mathtext/row_count) | Number of rows in the matrix |
| [column_count](/slides/python-net/aspose.slides.mathtext/column_count) | Number of columns in the matrix |
| [hide_placeholders](/slides/python-net/aspose.slides.mathtext/hide_placeholders) | Hide the placeholders for empty matrix elements<br/>            Default: false |
| [base_justification](/slides/python-net/aspose.slides.mathtext/base_justification) | Specifies the vertical justification respect to surrounding text. <br/>            Possible values are top, bottom, and center.<br/>            Default: Center |
| [min_column_width](/slides/python-net/aspose.slides.mathtext/min_column_width) | Minimum column width in twips (1/20th of a point)<br/>            The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to <br/>            the MinColumnWidth to determine the total Matrix Column Spacing<br/>            (distance between the same edges of different columns).<br/>            Default: 0. |
| [column_gap_rule](/slides/python-net/aspose.slides.mathtext/column_gap_rule) | The type of horizontal spacing between columns of a matrix; <br/>            Horizontal spacing units can be ems or points (stored as twips).<br/>            Default: SingleSpacingGap (0) |
| [column_gap](/slides/python-net/aspose.slides.mathtext/column_gap) | The value of horizontal spacing between columns of a matrix;<br/>            If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)<br/>            If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments.<br/>            In other cases ignored.<br/>            Default: 0 |
| [row_gap_rule](/slides/python-net/aspose.slides.mathtext/row_gap_rule) | The type of vertical spacing between rows of a matrix; <br/>            Vertical spacing units can be lines or points (stored as twips).<br/>            Default: SingleSpacingGap (0) |
| [row_gap](/slides/python-net/aspose.slides.mathtext/row_gap) | The value of vertical spacing between rows of a matrix;<br/>            If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)<br/>            If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines.<br/>            Default: 0 |
| [as_i_math_element](/slides/python-net/aspose.slides.mathtext/as_i_math_element) | Allows to get base IMathElement interface<br/>            :py:class:`aspose.slides.mathtext.IMathElement` |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#IMathElement-MathFractionTypes) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#string-MathFractionTypes) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#char-char) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#MathFunctionsOfOneArgument) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#MathFunctionsOfTwoArguments-IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#MathFunctionsOfTwoArguments-string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#IMathElement-IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#string-string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#IMathElement-IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#string-string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#MathNaryOperatorTypes-IMathElement-IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#MathNaryOperatorTypes-string-string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#MathIntegralTypes-IMathElement-IMathElement-MathLimitLocations) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#MathIntegralTypes-IMathElement-IMathElement) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#MathIntegralTypes) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#MathIntegralTypes-string-string-MathLimitLocations) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#MathIntegralTypes-string-string) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#char-MathTopBotPositions-MathTopBotPositions) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#int) | Get the horizontal alignment of the specified column |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#int-MathHorizontalAlignment) | Set the horizontal alignment of the specified column |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#int-int-MathHorizontalAlignment) | Set the horizontal alignment of the specified columns |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#int) | Insert a new row before the specified one<br/>            Initially all elements in the new row are null. |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#int) | Insert a new row after the specified one<br/>            Initially all elements in the new row are null. |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#int) | Deletes the specified row |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#int) | Insert a new column before the specified one<br/>            Initially all elements in the new column are null. |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#int) | Insert a new column after the specified one<br/>            Initially all elements in the new column are null. |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#int) | Deletes the specified column |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#char) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#) |  |
| [__init__](/slides/python-net/aspose.slides.mathtext/imathmatrix/#) |  |

