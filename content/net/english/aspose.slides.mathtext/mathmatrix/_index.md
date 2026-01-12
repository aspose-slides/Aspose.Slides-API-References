---
title: MathMatrix
second_title: Aspose.Sildes for .NET API Reference
description: Specifies the Matrix object consisting of child elements laid out in one or more rows and columns. It is important to note that matrices do not have built in delimiters. To place the matrix in the brackets you should use the delimiter object IMathDelimiter. Null arguments can be used to create gaps in matrices.
type: docs
weight: 8810
url: /aspose.slides.mathtext/mathmatrix/
---

## MathMatrix class

Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. It is important to note that matrices do not have built in delimiters. To place the matrix in the brackets you should use the delimiter object (IMathDelimiter). Null arguments can be used to create gaps in matrices.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Constructors

| Name | Description |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Initializes a new instance of the MathMatrix class. |

## Properties

| Name | Description |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Number of columns in the matrix |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. In other cases ignored. Default: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Hide the placeholders for empty matrix elements Default: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Element of matrix |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Number of rows in the matrix |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. Default: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). Default: SingleSpacingGap (0) |

## Methods

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Sets an accent mark (a character on the top of this element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Takes specified function using this instance as the argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Takes specified function using this instance as the argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Takes specified function using this instance as the argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Takes specified function using this instance as the argument and specified additional argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Takes specified function using this instance as the argument and specified additional argument |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Deletes the specified column |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Deletes the specified row |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Creates a fraction with this numerator and specified denominator |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Creates a fraction with this numerator and specified denominator |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Encloses a math element in parenthesis |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Takes a function of an argument using this instance as the function name |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Takes a function of an argument using this instance as the function name |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Get children elements |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Get the horizontal alignment of the specified column |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Places this element in a group using a bottom curly bracket |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Insert a new column after the specified one Initially all elements in the new column are null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Insert a new column before the specified one Initially all elements in the new column are null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Insert a new row after the specified one Initially all elements in the new row are null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Insert a new row before the specified one Initially all elements in the new row are null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Takes the integral without limits |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Takes the integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Takes the integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Takes the integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Takes the integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Joins a mathematical element and forms a mathematical block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Joins a mathematical text and forms a mathematical block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Creates a N-ary operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Creates a N-ary operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Sets a bar on the top of this element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specifies the mathematical root of the given degree from the specified argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specifies the mathematical root of the given degree from the specified argument. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Set the horizontal alignment of the specified column |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Set the horizontal alignment of the specified columns |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Takes lower limit |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Takes lower limit |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Creates subscript |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Creates subscript |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Creates subscript and superscript on the left |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Creates subscript and superscript on the left |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Creates subscript and superscript on the right |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Creates subscript and superscript on the right |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Creates superscript |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Creates superscript |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Takes upper limit |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Takes upper limit |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Places this element in a border-box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Places this element in a border-box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Places this element in a non-visual box (logical grouping) which is used to group components of an equation or other instance of mathematical text. A boxed object can (for example) serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Puts in a vertical array |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Sets a bar on the bottom of this element |

### Examples

Example:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### See Also

* class [MathElementBase](../mathelementbase)
* interface [IMathMatrix](../imathmatrix)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
