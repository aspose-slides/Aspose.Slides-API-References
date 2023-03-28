---
title: "Aspose::Slides::MathText"
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 144
url: /cpp/aspose.slides.mathtext/
---



## Classes

| Class | Description |
| --- | --- |
| [BaseScript](./basescript/) | Math script |
| [IHasControlCharacterProperties](./ihascontrolcharacterproperties/) | [IMathElement](./imathelement/) with [Control](../aspose.slides/control/) Character Properties |
| [IMathAccent](./imathaccent/) | Specifies the accent function, consisting of a base and a combining diacritical mark Example: \\uD835\\uDC4E\\u0301 |
| [IMathAccentFactory](./imathaccentfactory/) | Allows to create a math accent |
| [IMathArray](./imatharray/) | Specifies a vertical array of equations or any mathematical objects |
| [IMathArrayFactory](./imatharrayfactory/) | Allows to create a math array |
| [IMathBar](./imathbar/) | Specifies the bar function, consisting of a base argument and an overbar or underbar |
| [IMathBarFactory](./imathbarfactory/) | Allows to create a math bar |
| [IMathBlock](./imathblock/) | Specifies an instance of mathematical text that contained within a [MathParagraph](./mathparagraph/) and starts on its own line. All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block. |
| [IMathBlockCollection](./imathblockcollection/) | Collection of math blocks ([IMathBlock](./imathblock/)) |
| [IMathBlockFactory](./imathblockfactory/) | Allows to create a math block |
| [IMathBorderBox](./imathborderbox/) | Draws a rectangular or some other border around the [IMathElement](./imathelement/). |
| [IMathBorderBoxFactory](./imathborderboxfactory/) | Allows to create a math border box |
| [IMathBox](./imathbox/) | Specifies the logical boxing (packaging) of mathematical element. For example, a boxed object can serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within. For example, the \"==\" operator should be boxed to prevent line breaks. |
| [IMathBoxFactory](./imathboxfactory/) | Allows to create a math box |
| [IMathDelimiter](./imathdelimiter/) | Specifies the delimiter object, consisting of opening and closing characters (such as parentheses, braces, brackets, and vertical bars), and one or more mathematical elements inside, separated by a specified character. Examples: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [IMathDelimiterFactory](./imathdelimiterfactory/) | Allows to create a math delimiter |
| [IMathElement](./imathelement/) | Base interface of any mathematical element: fraction, mathmatical text, function, expression with multiple elements etc |
| [IMathElementCollection](./imathelementcollection/) | Represents a collection of mathematical elements (MathElement). |
| [IMathematicalText](./imathematicaltext/) | Mathematical text |
| [IMathematicalTextFactory](./imathematicaltextfactory/) | Allows to create a [MathematicalText](./mathematicaltext/) element |
| [IMathFraction](./imathfraction/) | Specifies the fraction object, consisting of a numerator and denominator separated by a fraction bar. The fraction bar can be horizontal or diagonal, depending on the fraction properties. The fraction object is also used to represent the stack function, which places one element above another, with no fraction bar. |
| [IMathFractionFactory](./imathfractionfactory/) | Allows to create a math fraction |
| [IMathFunction](./imathfunction/) | Specifies a function of an argument. |
| [IMathFunctionFactory](./imathfunctionfactory/) | Allows to create a math function |
| [IMathGroupingCharacter](./imathgroupingcharacter/) | Specifies a grouping symbol above or below an expression, usually to highlight the relationship between elements |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory/) | Allows to create a math grouping character |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement/) | Specifies the Sub-Superscript object, which consists of a base and a subscript and superscript placed to the left of the base. |
| [IMathLimit](./imathlimit/) | Specifies the Limit object, consisting of text on the baseline and reduced-size text immediately above or below it. |
| [IMathLimitFactory](./imathlimitfactory/) | Allows to create [IMathLimit](./imathlimit/) |
| [IMathMatrix](./imathmatrix/) | Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. It is important to note that matrices do not have built in delimiters. To place the matrix in the brackets you should use the delimiter object ([IMathDelimiter](./imathdelimiter/)). Null arguments can be used to create gaps in matrices. |
| [IMathMatrixFactory](./imathmatrixfactory/) | Allows to create a math matrix |
| [IMathNaryOperator](./imathnaryoperator/) | Specifies an N-ary mathematical object, such as Summation and Integral. It consists of an operator, a base (or operand), and optional upper and lower limits. Examples of N-ary operators are: Summation, Union, Intersection, Integral |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory/) | Allows to create [IMathNaryOperator](./imathnaryoperator/) |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties/) | Specifies properties of [IMathNaryOperator](./imathnaryoperator/) |
| [IMathParagraph](./imathparagraph/) | Mathematical paragraph that is a container for mathematical blocks ([IMathBlock](./imathblock/)) |
| [IMathParagraphFactory](./imathparagraphfactory/) | Allows to create a math paragraph |
| [IMathPortion](./imathportion/) | Represents a portion with mathematical context inside. |
| [IMathRadical](./imathradical/) | Specifies the radical function, consisting of a base, and an optional degree. Example of radical object is \\u221A\\uD835\\uDC65. |
| [IMathRadicalFactory](./imathradicalfactory/) | Allows to create math radical |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement/) | Specifies the Sub-Superscript object, which consists of a base and a subscript and superscript placed to the right of the base. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) | Allows to create [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [IMathSubscriptElement](./imathsubscriptelement/) | Specifies the subscript object, which consists of a base and a reduced-size subscript placed below and to the right. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory/) | Allows to create [IMathSubscriptElement](./imathsubscriptelement/) |
| [IMathSuperscriptElement](./imathsuperscriptelement/) | Specifies the superscript object, which consists of a base and a reduced-size superscript placed above and to the right |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory/) | Allows to create [IMathSuperscriptElement](./imathsuperscriptelement/) |
| [MathAccent](./mathaccent/) | Specifies the accent function, consisting of a base and a combining diacritical mark Example: \\uD835\\uDC4E\\u0301 |
| [MathAccentFactory](./mathaccentfactory/) | Allows to create a math accent |
| [MathArray](./matharray/) | Specifies a vertical array of equations or any mathematical objects |
| [MathArrayFactory](./matharrayfactory/) | Allows to create a math array |
| [MathBar](./mathbar/) | Specifies the bar function, consisting of a base argument and an overbar or underbar |
| [MathBarFactory](./mathbarfactory/) | Allows to create a math bar |
| [MathBlock](./mathblock/) | Specifies an instance of mathematical text that contained within a [MathParagraph](./mathparagraph/) and starts on its own line. All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block. |
| [MathBlockFactory](./mathblockfactory/) | Allows to create a math block |
| [MathBorderBox](./mathborderbox/) | Draws a rectangular or some other border around the [IMathElement](./imathelement/). |
| [MathBorderBoxFactory](./mathborderboxfactory/) | Allows to create a math border box |
| [MathBox](./mathbox/) | Specifies the logical boxing (packaging) of mathematical element. For example, a boxed object can serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within. For example, the \"==\" operator should be boxed to prevent line breaks. |
| [MathBoxFactory](./mathboxfactory/) | Allows to create a math box |
| [MathDelimiter](./mathdelimiter/) | Specifies the delimiter object, consisting of opening and closing characters (such as parentheses, braces, brackets, and vertical bars), and one or more mathematical elements inside, separated by a specified character. Examples: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [MathDelimiterFactory](./mathdelimiterfactory/) | Allows to create a math delimiter |
| [MathElementBase](./mathelementbase/) | Base class for [IMathElement](./imathelement/) with the implementation of some methods that are common to all inherited classes For internal use only. Inherited class must be [IMathElement](./imathelement/). |
| [MathematicalText](./mathematicaltext/) | Mathematical text |
| [MathematicalTextFactory](./mathematicaltextfactory/) | Allows to create a [MathematicalText](./mathematicaltext/) element |
| [MathFraction](./mathfraction/) | Specifies the fraction object, consisting of a numerator and denominator separated by a fraction bar. The fraction bar can be horizontal or diagonal, depending on the fraction properties. The fraction object is also used to represent the stack function, which places one element above another, with no fraction bar. |
| [MathFractionFactory](./mathfractionfactory/) | Allows to create a math fraction |
| [MathFunction](./mathfunction/) | Specifies a function of an argument. |
| [MathFunctionFactory](./mathfunctionfactory/) | Allows to create a math function |
| [MathGroupingCharacter](./mathgroupingcharacter/) | Specifies a grouping symbol above or below an expression, usually to highlight the relationship between elements |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory/) | Allows to create a math grouping character |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement/) | Specifies the Sub-Superscript object, which consists of a base and a subscript and superscript placed to the left of the base. |
| [MathLimit](./mathlimit/) | Specifies the Limit object, consisting of text on the baseline and reduced-size text immediately above or below it. |
| [MathLimitFactory](./mathlimitfactory/) | Allows to create [IMathLimit](./imathlimit/) |
| [MathMatrix](./mathmatrix/) | Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. It is important to note that matrices do not have built in delimiters. To place the matrix in the brackets you should use the delimiter object ([IMathDelimiter](./imathdelimiter/)). Null arguments can be used to create gaps in matrices. |
| [MathMatrixFactory](./mathmatrixfactory/) | Allows to create a math matrix |
| [MathNaryOperator](./mathnaryoperator/) | Specifies an N-ary mathematical object, such as Summation and Integral. It consists of an operator, a base (or operand), and optional upper and lower limits. Examples of N-ary operators are: Summation, Union, Intersection, Integral |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory/) | Allows to create [IMathNaryOperator](./imathnaryoperator/) |
| [MathParagraph](./mathparagraph/) | Mathematical paragraph that is a container for mathematical blocks ([IMathBlock](./imathblock/)) |
| [MathParagraphFactory](./mathparagraphfactory/) | Allows to create a math paragraph |
| [MathPortion](./mathportion/) | Represents a portion with mathematical context inside. |
| [MathRadical](./mathradical/) | Specifies the radical function, consisting of a base, and an optional degree. Example of radical object is \\u221A\\uD835\\uDC65. |
| [MathRadicalFactory](./mathradicalfactory/) | Allows to create math radical |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement/) | Specifies the Sub-Superscript object, which consists of a base and a subscript and superscript placed to the right of the base. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory/) | Allows to create [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [MathSubscriptElement](./mathsubscriptelement/) | Specifies the subscript object, which consists of a base and a reduced-size subscript placed below and to the right. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory/) | Allows to create [IMathSubscriptElement](./imathsubscriptelement/) |
| [MathSuperscriptElement](./mathsuperscriptelement/) | Specifies the superscript object, which consists of a base and a reduced-size superscript placed above and to the right |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory/) | Allows to create [IMathSuperscriptElement](./imathsuperscriptelement/) |
## Enums

| Enum | Description |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape/) | The location and size of the delimiters relative to the content of the operands |
| [MathFractionTypes](./mathfractiontypes/) | Fraction Types |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument/) | Common mathematical functions of one argument |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments/) | Common mathematical functions of two arguments |
| [MathHorizontalAlignment](./mathhorizontalalignment/) | Horizontal Alignment |
| [MathIntegralTypes](./mathintegraltypes/) | Mathematical integral types |
| [MathJustification](./mathjustification/) | Specifies justification of the math paragraph (a series of adjacent instances of mathematical text within the same paragraph) |
| [MathLimitLocations](./mathlimitlocations/) | Location of limits (subscript/superscript) in n-ary operators. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes/) | Nary operator [IMathNaryOperator](./imathnaryoperator/) types (excluding integrals) For integrals [MathIntegralTypes](./mathintegraltypes/) |
| [MathRowSpacingRule](./mathrowspacingrule/) | The type of vertical spacing between columns in a matrix or array |
| [MathSpacingRules](./mathspacingrules/) | Types of gap (horizontal spacing) between columns of a matrix |
| [MathTopBotPositions](./mathtopbotpositions/) | Top/bottom positions enumeration |
| [MathVerticalAlignment](./mathverticalalignment/) | Vertical Alignment |
