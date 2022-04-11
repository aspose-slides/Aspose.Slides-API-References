---
title: Aspose.Slides.MathText
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 120
url: /net/aspose.slides.mathtext/
---


## Classes

| Class | Description |
| --- | --- |
| abstract class [BaseScript](./basescript) | Math script |
| class [MathAccent](./mathaccent) | Specifies the accent function, consisting of a base and a combining diacritical mark Example: 𝑎́ |
| class [MathAccentFactory](./mathaccentfactory) | Allows to create a math accent |
| class [MathArray](./matharray) | Specifies a vertical array of equations or any mathematical objects |
| class [MathArrayFactory](./matharrayfactory) | Allows to create a math array |
| class [MathBar](./mathbar) | Specifies the bar function, consisting of a base argument and an overbar or underbar |
| class [MathBarFactory](./mathbarfactory) | Allows to create a math bar |
| class [MathBlock](./mathblock) | Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line. All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block. |
| class [MathBlockFactory](./mathblockfactory) | Allows to create a math block |
| class [MathBorderBox](./mathborderbox) | Draws a rectangular or some other border around the IMathElement. |
| class [MathBorderBoxFactory](./mathborderboxfactory) | Allows to create a math border box |
| class [MathBox](./mathbox) | Specifies the logical boxing (packaging) of mathematical element. For example, a boxed object can serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within. For example, the "==" operator should be boxed to prevent line breaks. |
| class [MathBoxFactory](./mathboxfactory) | Allows to create a math box |
| class [MathDelimiter](./mathdelimiter) | Specifies the delimiter object, consisting of opening and closing characters (such as parentheses, braces, brackets, and vertical bars), and one or more mathematical elements inside, separated by a specified character. Examples: (𝑥2); [𝑥2&#x7C;𝑦2] |
| class [MathDelimiterFactory](./mathdelimiterfactory) | Allows to create a math delimiter |
| abstract class [MathElementBase](./mathelementbase) | Base class for IMathElement with the implementation of some methods that are common to all inherited classes For internal use only. Inherited class must be IMathElement. |
| class [MathematicalText](./mathematicaltext) | Mathematical text |
| class [MathematicalTextFactory](./mathematicaltextfactory) | Allows to create a MathematicalText element |
| class [MathFraction](./mathfraction) | Specifies the fraction object, consisting of a numerator and denominator separated by a fraction bar. The fraction bar can be horizontal or diagonal, depending on the fraction properties. The fraction object is also used to represent the stack function, which places one element above another, with no fraction bar. |
| class [MathFractionFactory](./mathfractionfactory) | Allows to create a math fraction |
| class [MathFunction](./mathfunction) | Specifies a function of an argument. |
| class [MathFunctionFactory](./mathfunctionfactory) | Allows to create a math function |
| class [MathGroupingCharacter](./mathgroupingcharacter) | Specifies a grouping symbol above or below an expression, usually to highlight the relationship between elements |
| class [MathGroupingCharacterFactory](./mathgroupingcharacterfactory) | Allows to create a math grouping character |
| class [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement) | Specifies the Sub-Superscript object, which consists of a base and a subscript and superscript placed to the left of the base. |
| class [MathLimit](./mathlimit) | Specifies the Limit object, consisting of text on the baseline and reduced-size text immediately above or below it. |
| class [MathLimitFactory](./mathlimitfactory) | Allows to create IMathLimit |
| class [MathMatrix](./mathmatrix) | Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. It is important to note that matrices do not have built in delimiters. To place the matrix in the brackets you should use the delimiter object (IMathDelimiter). Null arguments can be used to create gaps in matrices. |
| class [MathMatrixFactory](./mathmatrixfactory) | Allows to create a math matrix |
| class [MathNaryOperator](./mathnaryoperator) | Specifies an N-ary mathematical object, such as Summation and Integral. It consists of an operator, a base (or operand), and optional upper and lower limits. Examples of N-ary operators are: Summation, Union, Intersection, Integral |
| class [MathNaryOperatorFactory](./mathnaryoperatorfactory) | Allows to create IMathNaryOperator |
| class [MathParagraph](./mathparagraph) | Mathematical paragraph that is a container for mathematical blocks (IMathBlock) |
| class [MathParagraphFactory](./mathparagraphfactory) | Allows to create a math paragraph |
| class [MathPortion](./mathportion) | Represents a portion with mathematical context inside. |
| class [MathRadical](./mathradical) | Specifies the radical function, consisting of a base, and an optional degree. Example of radical object is √𝑥. |
| class [MathRadicalFactory](./mathradicalfactory) | Allows to create math radical |
| class [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement) | Specifies the Sub-Superscript object, which consists of a base and a subscript and superscript placed to the right of the base. |
| class [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory) | Allows to create IMathRightSubSuperscriptElementFactory |
| class [MathSubscriptElement](./mathsubscriptelement) | Specifies the subscript object, which consists of a base and a reduced-size subscript placed below and to the right. |
| class [MathSubscriptElementFactory](./mathsubscriptelementfactory) | Allows to create IMathSubscriptElement |
| class [MathSuperscriptElement](./mathsuperscriptelement) | Specifies the superscript object, which consists of a base and a reduced-size superscript placed above and to the right |
| class [MathSuperscriptElementFactory](./mathsuperscriptelementfactory) | Allows to create IMathSuperscriptElement |
## Interfaces

| Interface | Description |
| --- | --- |
| interface [IMathAccent](./imathaccent) | Specifies the accent function, consisting of a base and a combining diacritical mark Example: 𝑎́ |
| interface [IMathAccentFactory](./imathaccentfactory) | Allows to create a math accent |
| interface [IMathArray](./imatharray) | Specifies a vertical array of equations or any mathematical objects |
| interface [IMathArrayFactory](./imatharrayfactory) | Allows to create a math array |
| interface [IMathBar](./imathbar) | Specifies the bar function, consisting of a base argument and an overbar or underbar |
| interface [IMathBarFactory](./imathbarfactory) | Allows to create a math bar |
| interface [IMathBlock](./imathblock) | Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line. All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block. |
| interface [IMathBlockCollection](./imathblockcollection) | Collection of math blocks (IMathBlock) |
| interface [IMathBlockFactory](./imathblockfactory) | Allows to create a math block |
| interface [IMathBorderBox](./imathborderbox) | Draws a rectangular or some other border around the IMathElement. |
| interface [IMathBorderBoxFactory](./imathborderboxfactory) | Allows to create a math border box |
| interface [IMathBox](./imathbox) | Specifies the logical boxing (packaging) of mathematical element. For example, a boxed object can serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within. For example, the "==" operator should be boxed to prevent line breaks. |
| interface [IMathBoxFactory](./imathboxfactory) | Allows to create a math box |
| interface [IMathDelimiter](./imathdelimiter) | Specifies the delimiter object, consisting of opening and closing characters (such as parentheses, braces, brackets, and vertical bars), and one or more mathematical elements inside, separated by a specified character. Examples: (𝑥2); [𝑥2&#x7C;𝑦2] |
| interface [IMathDelimiterFactory](./imathdelimiterfactory) | Allows to create a math delimiter |
| interface [IMathElement](./imathelement) | Base interface of any mathematical element: fraction, mathmatical text, function, expression with multiple elements etc |
| interface [IMathElementCollection](./imathelementcollection) | Represents a collection of mathematical elements (MathElement). |
| interface [IMathematicalText](./imathematicaltext) | Mathematical text |
| interface [IMathematicalTextFactory](./imathematicaltextfactory) | Allows to create a MathematicalText element |
| interface [IMathFraction](./imathfraction) | Specifies the fraction object, consisting of a numerator and denominator separated by a fraction bar. The fraction bar can be horizontal or diagonal, depending on the fraction properties. The fraction object is also used to represent the stack function, which places one element above another, with no fraction bar. |
| interface [IMathFractionFactory](./imathfractionfactory) | Allows to create a math fraction |
| interface [IMathFunction](./imathfunction) | Specifies a function of an argument. |
| interface [IMathFunctionFactory](./imathfunctionfactory) | Allows to create a math function |
| interface [IMathGroupingCharacter](./imathgroupingcharacter) | Specifies a grouping symbol above or below an expression, usually to highlight the relationship between elements |
| interface [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory) | Allows to create a math grouping character |
| interface [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement) | Specifies the Sub-Superscript object, which consists of a base and a subscript and superscript placed to the left of the base. |
| interface [IMathLimit](./imathlimit) | Specifies the Limit object, consisting of text on the baseline and reduced-size text immediately above or below it. |
| interface [IMathLimitFactory](./imathlimitfactory) | Allows to create IMathLimit |
| interface [IMathMatrix](./imathmatrix) | Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. It is important to note that matrices do not have built in delimiters. To place the matrix in the brackets you should use the delimiter object (IMathDelimiter). Null arguments can be used to create gaps in matrices. |
| interface [IMathMatrixFactory](./imathmatrixfactory) | Allows to create a math matrix |
| interface [IMathNaryOperator](./imathnaryoperator) | Specifies an N-ary mathematical object, such as Summation and Integral. It consists of an operator, a base (or operand), and optional upper and lower limits. Examples of N-ary operators are: Summation, Union, Intersection, Integral |
| interface [IMathNaryOperatorFactory](./imathnaryoperatorfactory) | Allows to create IMathNaryOperator |
| interface [IMathNaryOperatorProperties](./imathnaryoperatorproperties) | Specifies properties of IMathNaryOperator |
| interface [IMathParagraph](./imathparagraph) | Mathematical paragraph that is a container for mathematical blocks (IMathBlock) |
| interface [IMathParagraphFactory](./imathparagraphfactory) | Allows to create a math paragraph |
| interface [IMathPortion](./imathportion) | Represents a portion with mathematical context inside. |
| interface [IMathRadical](./imathradical) | Specifies the radical function, consisting of a base, and an optional degree. Example of radical object is √𝑥. |
| interface [IMathRadicalFactory](./imathradicalfactory) | Allows to create math radical |
| interface [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement) | Specifies the Sub-Superscript object, which consists of a base and a subscript and superscript placed to the right of the base. |
| interface [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory) | Allows to create IMathRightSubSuperscriptElementFactory |
| interface [IMathSubscriptElement](./imathsubscriptelement) | Specifies the subscript object, which consists of a base and a reduced-size subscript placed below and to the right. |
| interface [IMathSubscriptElementFactory](./imathsubscriptelementfactory) | Allows to create IMathSubscriptElement |
| interface [IMathSuperscriptElement](./imathsuperscriptelement) | Specifies the superscript object, which consists of a base and a reduced-size superscript placed above and to the right |
| interface [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory) | Allows to create IMathSuperscriptElement |
## Enumeration

| Enumeration | Description |
| --- | --- |
| enum [MathDelimiterShape](./mathdelimitershape) | The location and size of the delimiters relative to the content of the operands |
| enum [MathFractionTypes](./mathfractiontypes) | Fraction Types |
| enum [MathFunctionsOfOneArgument](./mathfunctionsofoneargument) | Common mathematical functions of one argument |
| enum [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments) | Common mathematical functions of two arguments |
| enum [MathHorizontalAlignment](./mathhorizontalalignment) | Horizontal Alignment |
| enum [MathIntegralTypes](./mathintegraltypes) | Mathematical integral types |
| enum [MathJustification](./mathjustification) | Specifies justification of the math paragraph (a series of adjacent instances of mathematical text within the same paragraph) |
| enum [MathLimitLocations](./mathlimitlocations) | Location of limits (subscript/superscript) in n-ary operators. |
| enum [MathNaryOperatorTypes](./mathnaryoperatortypes) | Nary operator IMathNaryOperator types (excluding integrals) For integrals [`MathIntegralTypes`](aspose.slides.mathtext/mathintegraltypes) |
| enum [MathRowSpacingRule](./mathrowspacingrule) | The type of vertical spacing between columns in a matrix or array |
| enum [MathSpacingRules](./mathspacingrules) | Types of gap (horizontal spacing) between columns of a matrix |
| enum [MathTopBotPositions](./mathtopbotpositions) | Top/bottom positions enumeration |
| enum [MathVerticalAlignment](./mathverticalalignment) | Vertical Alignment |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
