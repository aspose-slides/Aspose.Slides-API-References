---
title: aspose.slides.mathtext
second_title: Aspose.Slides pro Python přes .NET API Referenci
description: 
type: docs
url: /cs/aspose.slides.mathtext/
---
Obsahuje třídy pro práci s matematickým textem v prezentacích Microsoft PowerPoint.

## Třídy

| Třída | Popis |
| :- | :- |
| [`BaseScript`](/slides/python-net/cs/aspose.slides.mathtext/basescript/) | Math script |
| [`IMathAccent`](/slides/python-net/cs/aspose.slides.mathtext/imathaccent/) | Určuje akcentní funkci, skládající se ze základu a kombinujícího diakritického znaménka<br/>            Example: 𝑎́ |
| [`IMathAccentFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathaccentfactory/) | Umožňuje vytvořit matematický akcent |
| [`IMathArray`](/slides/python-net/cs/aspose.slides.mathtext/imatharray/) | Určuje vertikální pole rovnic nebo jakýchkoli matematických objektů |
| [`IMathArrayFactory`](/slides/python-net/cs/aspose.slides.mathtext/imatharrayfactory/) | Umožňuje vytvořit matematické pole |
| [`IMathBar`](/slides/python-net/cs/aspose.slides.mathtext/imathbar/) | Určuje funkci pruhu, skládající se ze základního argumentu a horního nebo spodního pruhu |
| [`IMathBarFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathbarfactory/) | Umožňuje vytvořit matematický pruh |
| [`IMathBlock`](/slides/python-net/cs/aspose.slides.mathtext/imathblock/) | Určuje instanci matematického textu, která je obsažena v MathParagraph a začíná na samostatném řádku.<br/>            All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block. |
| [`IMathBlockCollection`](/slides/python-net/cs/aspose.slides.mathtext/imathblockcollection/) | Collection of math blocks (IMathBlock) |
| [`IMathBlockFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathblockfactory/) | Umožňuje vytvořit matematický blok |
| [`IMathBorderBox`](/slides/python-net/cs/aspose.slides.mathtext/imathborderbox/) | Draws a rectangular or some other border around the IMathElement. |
| [`IMathBorderBoxFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathborderboxfactory/) | Umožňuje vytvořit matematický okrajový rámeček |
| [`IMathBox`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/) | Určuje logické zabalení (balení) matematického elementu.<br/>            For example, a boxed object can serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within.<br/>            For example, the "==" operator should be boxed to prevent line breaks. |
| [`IMathBoxFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathboxfactory/) | Umožňuje vytvořit matematickou krabici |
| [`IMathDelimiter`](/slides/python-net/cs/aspose.slides.mathtext/imathdelimiter/) | Určuje objekt oddělovače, skládající se z otevíracích a zavíracích znaků (such as parentheses, <br/>            braces, brackets, and vertical bars), and one or more mathematical elements inside, separated by a specified character.<br/>            Examples: (𝑥2); [𝑥2\|𝑦2] |
| [`IMathDelimiterFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathdelimiterfactory/) | Umožňuje vytvořit matematický oddělovač |
| [`IMathElement`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/) | Base interface of any mathematical element: <br/>            fraction, mathmatical text, function, expression with multiple elements etc |
| [`IMathElementCollection`](/slides/python-net/cs/aspose.slides.mathtext/imathelementcollection/) | Represents a collection of mathematical elements (MathElement). |
| [`IMathFraction`](/slides/python-net/cs/aspose.slides.mathtext/imathfraction/) | Určuje objekt zlomku, skládající se z čitatele a jmenovatele oddělených čarou zlomku.<br/>            The fraction bar can be horizontal or diagonal, depending on the fraction properties.<br/>            The fraction object is also used to represent the stack function, which places one element above another, with no fraction bar. |
| [`IMathFractionFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathfractionfactory/) | Umožňuje vytvořit matematický zlomek |
| [`IMathFunction`](/slides/python-net/cs/aspose.slides.mathtext/imathfunction/) | Specifies a function of an argument. |
| [`IMathFunctionFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathfunctionfactory/) | Umožňuje vytvořit matematickou funkci |
| [`IMathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacter/) | Určuje seskupovací znak nad nebo pod výrazem, obvykle pro zvýraznění vztahu mezi elementy |
| [`IMathGroupingCharacterFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathgroupingcharacterfactory/) | Umožňuje vytvořit seskupovací znak |
| [`IMathLeftSubSuperscriptElement`](/slides/python-net/cs/aspose.slides.mathtext/imathleftsubsuperscriptelement/) | Určuje Sub-Superscript objekt, který se skládá ze základu <br/>            and a subscript and superscript placed to the left of the base. |
| [`IMathLimit`](/slides/python-net/cs/aspose.slides.mathtext/imathlimit/) | Určuje Limit objekt, skládající se z textu na základní lince a zmenšeného textu bezprostředně nad nebo pod ním. |
| [`IMathLimitFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathlimitfactory/) | Allows to create IMathLimit |
| [`IMathMatrix`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/) | Určuje Matrix objekt, skládající se z podřízených elementů uspořádaných v jednom nebo více řádcích a sloupcích. <br/>            It is important to note that matrices do not have built in delimiters. <br/>            To place the matrix in the brackets you should use the delimiter object (IMathDelimiter).<br/>            Null arguments can be used to create gaps in matrices. |
| [`IMathMatrixFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrixfactory/) | Umožňuje vytvořit matematickou matici |
| [`IMathNaryOperator`](/slides/python-net/cs/aspose.slides.mathtext/imathnaryoperator/) | Určuje N-ary matematický objekt, jako je Summation a Integral.<br/>            It consists of an operator, a base (or operand), and optional upper and lower limits. <br/>            Examples of N-ary operators are: Summation, Union, Intersection, Integral |
| [`IMathNaryOperatorFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathnaryoperatorfactory/) | Allows to create IMathNaryOperator |
| [`IMathNaryOperatorProperties`](/slides/python-net/cs/aspose.slides.mathtext/imathnaryoperatorproperties/) | Specifies properties of IMathNaryOperator |
| [`IMathParagraph`](/slides/python-net/cs/aspose.slides.mathtext/imathparagraph/) | Mathematical paragraph that is a container for mathematical blocks (IMathBlock) |
| [`IMathParagraphFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathparagraphfactory/) | Allows to create a math paragraph |
| [`IMathPhantom`](/slides/python-net/cs/aspose.slides.mathtext/imathphantom/) | Represents a phantom math object (<m:phant>) that affects the layout of its child element<br/>            without necessarily displaying it. A phantom can hide its base expression while preserving<br/>            its width, height, or depth to align formulas or reserve space. <br/>            Visibility and geometry behavior are controlled by properties such as Show, ZeroWid, ZeroAsc, <br/>            ZeroDesc, and Transp. |
| [`IMathPortion`](/slides/python-net/cs/aspose.slides.mathtext/imathportion/) | Represents a portion with mathematical context inside. |
| [`IMathRadical`](/slides/python-net/cs/aspose.slides.mathtext/imathradical/) | Určuje radikální funkci, skládající se ze základu a volitelného stupně.<br/>            Example of radical object is √𝑥. |
| [`IMathRadicalFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathradicalfactory/) | Allows to create math radical |
| [`IMathRightSubSuperscriptElement`](/slides/python-net/cs/aspose.slides.mathtext/imathrightsubsuperscriptelement/) | Určuje Sub-Superscript objekt, který se skládá ze základu <br/>            and a subscript and superscript placed to the right of the base. |
| [`IMathRightSubSuperscriptElementFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathrightsubsuperscriptelementfactory/) | Allows to create IMathRightSubSuperscriptElementFactory |
| [`IMathSubscriptElement`](/slides/python-net/cs/aspose.slides.mathtext/imathsubscriptelement/) | Určuje subscript objekt, který se skládá ze základu <br/>            and a reduced-size subscript placed below and to the right. |
| [`IMathSubscriptElementFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathsubscriptelementfactory/) | Allows to create IMathSubscriptElement |
| [`IMathSuperscriptElement`](/slides/python-net/cs/aspose.slides.mathtext/imathsuperscriptelement/) | Určuje superscript objekt, který se skládá ze základu <br/>            and a reduced-size superscript placed above and to the right |
| [`IMathSuperscriptElementFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathsuperscriptelementfactory/) | Allows to create IMathSuperscriptElement |
| [`IMathematicalText`](/slides/python-net/cs/aspose.slides.mathtext/imathematicaltext/) | Mathematical text |
| [`IMathematicalTextFactory`](/slides/python-net/cs/aspose.slides.mathtext/imathematicaltextfactory/) | Allows to create a MathematicalText element |
| [`MathAccent`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/) | Určuje akcentní funkci, skládající se ze základu a kombinujícího diakritického znaménka<br/>            Example: 𝑎́ |
| [`MathAccentFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathaccentfactory/) | Umožňuje vytvořit matematický akcent |
| [`MathArray`](/slides/python-net/cs/aspose.slides.mathtext/matharray/) | Určuje vertikální pole rovnic nebo jakýchkoli matematických objektů |
| [`MathArrayFactory`](/slides/python-net/cs/aspose.slides.mathtext/matharrayfactory/) | Umožňuje vytvořit matematické pole |
| [`MathBar`](/slides/python-net/cs/aspose.slides.mathtext/mathbar/) | Určuje funkci pruhu, skládající se ze základního argumentu a horního nebo spodního pruhu |
| [`MathBarFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathbarfactory/) | Umožňuje vytvořit matematický pruh |
| [`MathBlock`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/) | Určuje instanci matematického textu, která je obsažena v MathParagraph a začíná na samostatném řádku.<br/>            All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block. |
| [`MathBlockFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathblockfactory/) | Allows to create a math block |
| [`MathBorderBox`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/) | Draws a rectangular or some other border around the IMathElement. |
| [`MathBorderBoxFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathborderboxfactory/) | Allows to create a math border box |
| [`MathBox`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/) | Určuje logické zabalení (balení) matematického elementu.<br/>            For example, a boxed object can serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within.<br/>            For example, the "==" operator should be boxed to prevent line breaks. |
| [`MathBoxFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathboxfactory/) | Allows to create a math box |
| [`MathDelimiter`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/) | Určuje objekt oddělovače, skládající se z otevíracích a zavíracích znaků (such as parentheses, <br/>            braces, brackets, and vertical bars), and one or more mathematical elements inside, separated by a specified character.<br/>            Examples: (𝑥2); [𝑥2\|𝑦2] |
| [`MathDelimiterFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiterfactory/) | Allows to create a math delimiter |
| [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase/) | Base class for IMathElement with the implementation of some methods that are common to all inherited classes<br/>            For internal use only. Inherited class must be IMathElement. |
| [`MathFraction`](/slides/python-net/cs/aspose.slides.mathtext/mathfraction/) | Určuje objekt zlomku, skládající se z čitatele a jmenovatele oddělených čarou zlomku.<br/>            The fraction bar can be horizontal or diagonal, depending on the fraction properties.<br/>            The fraction object is also used to represent the stack function, which places one element above another, with no fraction bar. |
| [`MathFractionFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathfractionfactory/) | Allows to create a math fraction |
| [`MathFunction`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/) | Specifies a function of an argument. |
| [`MathFunctionFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathfunctionfactory/) | Allows to create a math function |
| [`MathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/) | Určuje seskupovací znak nad nebo pod výrazem, obvykle pro zvýraznění vztahu mezi elementy |
| [`MathGroupingCharacterFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacterfactory/) | Allows to create a math grouping character |
| [`MathLeftSubSuperscriptElement`](/slides/python-net/cs/aspose.slides.mathtext/mathleftsubsuperscriptelement/) | Určuje Sub-Superscript objekt, který se skládá ze základu <br/>            and a subscript and superscript placed to the left of the base. |
| [`MathLimit`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/) | Určuje Limit objekt, skládající se z textu na základní lince a zmenšeného textu bezprostředně nad nebo pod ním. |
| [`MathLimitFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathlimitfactory/) | Allows to create IMathLimit |
| [`MathMatrix`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/) | Určuje Matrix objekt, skládající se z podřízených elementů uspořádaných v jednom nebo více řádcích a sloupcích. <br/>            It is important to note that matrices do not have built in delimiters. <br/>            To place the matrix in the brackets you should use the delimiter object (IMathDelimiter).<br/>            Null arguments can be used to create gaps in matrices. |
| [`MathMatrixFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrixfactory/) | Allows to create a math matrix |
| [`MathNaryOperator`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/) | Určuje N-ary matematický objekt, jako je Summation a Integral.<br/>            It consists of an operator, a base (or operand), and optional upper and lower limits. <br/>            Examples of N-ary operators are: Summation, Union, Intersection, Integral |
| [`MathNaryOperatorFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperatorfactory/) | Allows to create IMathNaryOperator |
| [`MathParagraph`](/slides/python-net/cs/aspose.slides.mathtext/mathparagraph/) | Mathematical paragraph that is a container for mathematical blocks (IMathBlock) |
| [`MathParagraphFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathparagraphfactory/) | Allows to create a math paragraph |
| [`MathPhantom`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/) | Represents a phantom math object (<m:phant>) that affects the layout of its child element<br/>            without necessarily displaying it. A phantom can hide its base expression while preserving<br/>            its width, height, or depth to align formulas or reserve space. <br/>            Visibility and geometry behavior are controlled by properties such as Show, ZeroWid, ZeroAsc, <br/>            ZeroDesc, and Transp. |
| [`MathPortion`](/slides/python-net/cs/aspose.slides.mathtext/mathportion/) | Represents a portion with mathematical context inside. |
| [`MathRadical`](/slides/python-net/cs/aspose.slides.mathtext/mathradical/) | Určuje radikální funkci, skládající se ze základu a volitelného stupně.<br/>            Example of radical object is √𝑥. |
| [`MathRadicalFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathradicalfactory/) | Allows to create math radical |
| [`MathRightSubSuperscriptElement`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/) | Určuje Sub-Superscript objekt, který se skládá ze základu <br/>            and a subscript and superscript placed to the right of the base. |
| [`MathRightSubSuperscriptElementFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelementfactory/) | Allows to create IMathRightSubSuperscriptElementFactory |
| [`MathSubscriptElement`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/) | Určuje subscript objekt, který se skládá ze základu <br/>            and a reduced-size subscript placed below and to the right. |
| [`MathSubscriptElementFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelementfactory/) | Allows to create IMathSubscriptElement |
| [`MathSuperscriptElement`](/slides/python-net/cs/aspose.slides.mathtext/mathsuperscriptelement/) | Určuje superscript objekt, který se skládá ze základu <br/>            and a reduced-size superscript placed above and to the right |
| [`MathSuperscriptElementFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathsuperscriptelementfactory/) | Allows to create IMathSuperscriptElement |
| [`MathematicalText`](/slides/python-net/cs/aspose.slides.mathtext/mathematicaltext/) | Mathematical text |
| [`MathematicalTextFactory`](/slides/python-net/cs/aspose.slides.mathtext/mathematicaltextfactory/) | Allows to create a MathematicalText element |

## Výčty

| Výčet | Popis |
| :- | :- |
| [`MathDelimiterShape`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimitershape/) | The location and size of the delimiters relative to the content of the operands |
| [`MathFractionTypes`](/slides/python-net/cs/aspose.slides.mathtext/mathfractiontypes/) | Fraction Types |
| [`MathFunctionsOfOneArgument`](/slides/python-net/cs/aspose.slides.mathtext/mathfunctionsofoneargument/) | Common mathematical functions of one argument |
| [`MathFunctionsOfTwoArguments`](/slides/python-net/cs/aspose.slides.mathtext/mathfunctionsoftwoarguments/) | Common mathematical functions of two arguments |
| [`MathHorizontalAlignment`](/slides/python-net/cs/aspose.slides.mathtext/mathhorizontalalignment/) | Horizontal Alignment |
| [`MathIntegralTypes`](/slides/python-net/cs/aspose.slides.mathtext/mathintegraltypes/) | Mathematical integral types |
| [`MathJustification`](/slides/python-net/cs/aspose.slides.mathtext/mathjustification/) | Specifies justification of the math paragraph (a series of adjacent instances of mathematical text within the same paragraph) |
| [`MathLimitLocations`](/slides/python-net/cs/aspose.slides.mathtext/mathlimitlocations/) | Location of limits (subscript/superscript) in n-ary operators. |
| [`MathNaryOperatorTypes`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperatortypes/) | Nary operator IMathNaryOperator types (excluding integrals)<br/>            For integrals [`MathIntegralTypes`](/slides/python-net/cs/aspose.slides.mathtext/mathintegraltypes) |
| [`MathRowSpacingRule`](/slides/python-net/cs/aspose.slides.mathtext/mathrowspacingrule/) | The type of vertical spacing between columns in a matrix or array |
| [`MathSpacingRules`](/slides/python-net/cs/aspose.slides.mathtext/mathspacingrules/) | Types of gap (horizontal spacing) between columns of a matrix |
| [`MathTopBotPositions`](/slides/python-net/cs/aspose.slides.mathtext/mathtopbotpositions/) | Top/bottom positions enumeration |
| [`MathVerticalAlignment`](/slides/python-net/cs/aspose.slides.mathtext/mathverticalalignment/) | Vertical Alignment |