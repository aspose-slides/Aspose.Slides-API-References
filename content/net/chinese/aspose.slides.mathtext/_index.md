---
title: Aspose.Slides.MathText
second_title: Aspose.Sildes for .NET API Reference
description: 包含用于处理Microsoft PowerPoint演示文稿中的数学文本的类。
type: docs
weight: 120
url: /zh/aspose.slides.mathtext/
---

包含用于处理Microsoft PowerPoint演示文稿中的数学文本的类。

## 类

| 类 | 描述 |
| --- | --- |
| [BaseScript](./basescript) | 数学脚本 |
| [MathAccent](./mathaccent) | 指定音调功能，由基部和组合变音符号组成 示例：𝑎́ |
| [MathAccentFactory](./mathaccentfactory) | 允许创建数学音调 |
| [MathArray](./matharray) | 指定纵向数组的方程或任何数学对象 |
| [MathArrayFactory](./matharrayfactory) | 允许创建数学数组 |
| [MathBar](./mathbar) | 指定条形功能，由基部参数和上横线或下横线组成 |
| [MathBarFactory](./mathbarfactory) | 允许创建数学条 |
| [MathBlock](./mathblock) | 指定包含在MathParagraph中的数学文本实例，并独占一行。所有数学区域，包括方程、表达式、方程或表达式的数组和公式，都由数学块表示。 |
| [MathBlockFactory](./mathblockfactory) | 允许创建数学块 |
| [MathBorderBox](./mathborderbox) | 绘制一个矩形或其他边框围绕IMathElement。 |
| [MathBorderBoxFactory](./mathborderboxfactory) | 允许创建数学边框盒 |
| [MathBox](./mathbox) | 指定数学元素的逻辑包装（打包）。例如，盒装对象可以作为操作符仿真器，带或不带对齐点，作为换行点，或者被分组以不允许换行。在这种情况下，“==”操作符应被包装以防止换行。 |
| [MathBoxFactory](./mathboxfactory) | 允许创建数学盒 |
| [MathDelimiter](./mathdelimiter) | 指定分隔符对象，由开关字符（例如括号、大括号、方括号和竖线）组成，并包含一个或多个数学元素，中间由指定字符分隔。示例：（𝑥2）；[𝑥2&#x7C;𝑦2] |
| [MathDelimiterFactory](./mathdelimiterfactory) | 允许创建数学分隔符 |
| [MathElementBase](./mathelementbase) | IMathElement的基类，具有对所有继承类通用的一些方法的实现 仅供内部使用。继承类必须是IMathElement。 |
| [MathematicalText](./mathematicaltext) | 数学文本 |
| [MathematicalTextFactory](./mathematicaltextfactory) | 允许创建MathematicalText元素 |
| [MathFraction](./mathfraction) | 指定分数对象，由分子和分母组成，二者之间用分数线分隔。分数线可以是水平的或对角的，具体取决于分数属性。分数对象也用于表示堆叠函数，将一个元素放在另一个元素上方，无需分数线。 |
| [MathFractionFactory](./mathfractionfactory) | 允许创建数学分数 |
| [MathFunction](./mathfunction) | 指定参数的函数。 |
| [MathFunctionFactory](./mathfunctionfactory) | 允许创建数学函数 |
| [MathGroupingCharacter](./mathgroupingcharacter) | 指定一个符号，通常在表达式的上方或下方，以突出元素之间的关系 |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory) | 允许创建数学分组字符 |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement) | 指定下标和上标对象，它们位于基部的左侧。 |
| [MathLimit](./mathlimit) | 指定Limit对象，由基线上的文本和紧接其上方或下方的缩小文本组成。 |
| [MathLimitFactory](./mathlimitfactory) | 允许创建IMathLimit |
| [MathMatrix](./mathmatrix) | 指定Matrix对象，由一行或多行和一列中排列的子元素组成。需要注意的是，矩阵没有内置的分隔符。要将矩阵放在括号中，应使用分隔符对象（IMathDelimiter）。可以使用空参数在矩阵中创建间隙。 |
| [MathMatrixFactory](./mathmatrixfactory) | 允许创建数学矩阵 |
| [MathNaryOperator](./mathnaryoperator) | 指定N元数学对象，例如求和和积分。它由一个运算符、一个基（或操作数）以及可选的上限和下限组成。N元运算符的示例包括：求和、并集、交集、积分 |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory) | 允许创建IMathNaryOperator |
| [MathParagraph](./mathparagraph) | 数学段落，作为数学块（IMathBlock）的容器 |
| [MathParagraphFactory](./mathparagraphfactory) | 允许创建数学段落 |
| [MathPortion](./mathportion) | 表示包含数学上下文的一部分。 |
| [MathRadical](./mathradical) | 指定根号功能，由基部和可选角度组成。根号对象的示例为√𝑥。 |
| [MathRadicalFactory](./mathradicalfactory) | 允许创建数学根号 |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement) | 指定下标和上标对象，它们位于基部的右侧。 |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory) | 允许创建IMathRightSubSuperscriptElementFactory |
| [MathSubscriptElement](./mathsubscriptelement) | 指定下标对象，由基部和缩小的下标组成，位于下方且偏右。 |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory) | 允许创建IMathSubscriptElement |
| [MathSuperscriptElement](./mathsuperscriptelement) | 指定上标对象，由基部和缩小的上标组成，位于上方且偏右 |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory) | 允许创建IMathSuperscriptElement |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IMathAccent](./imathaccent) | 指定音调功能，由基部和组合变音符号组成 示例：𝑎́ |
| [IMathAccentFactory](./imathaccentfactory) | 允许创建数学音调 |
| [IMathArray](./imatharray) | 指定纵向数组的方程或任何数学对象 |
| [IMathArrayFactory](./imatharrayfactory) | 允许创建数学数组 |
| [IMathBar](./imathbar) | 指定条形功能，由基部参数和上横线或下横线组成 |
| [IMathBarFactory](./imathbarfactory) | 允许创建数学条 |
| [IMathBlock](./imathblock) | 指定包含在MathParagraph中的数学文本实例，并独占一行。所有数学区域，包括方程、表达式、方程或表达式的数组和公式，都由数学块表示。 |
| [IMathBlockCollection](./imathblockcollection) | 数学块集合（IMathBlock） |
| [IMathBlockFactory](./imathblockfactory) | 允许创建数学块 |
| [IMathBorderBox](./imathborderbox) | 绘制一个矩形或其他边框围绕IMathElement。 |
| [IMathBorderBoxFactory](./imathborderboxfactory) | 允许创建数学边框盒 |
| [IMathBox](./imathbox) | 指定数学元素的逻辑包装（打包）。例如，盒装对象可以作为操作符仿真器，带或不带对齐点，作为换行点，或者被分组以不允许换行。在这种情况下，“==”操作符应被包装以防止换行。 |
| [IMathBoxFactory](./imathboxfactory) | 允许创建数学盒 |
| [IMathDelimiter](./imathdelimiter) | 指定分隔符对象，由开关字符（例如括号、大括号、方括号和竖线）组成，并包含一个或多个数学元素，中间由指定字符分隔。示例：（𝑥2）；[𝑥2&#x7C;𝑦2] |
| [IMathDelimiterFactory](./imathdelimiterfactory) | 允许创建数学分隔符 |
| [IMathElement](./imathelement) | 任何数学元素的基接口：分数、数学文本、函数、包含多个元素的表达式等 |
| [IMathElementCollection](./imathelementcollection) | 表示数学元素的集合（MathElement）。 |
| [IMathematicalText](./imathematicaltext) | 数学文本 |
| [IMathematicalTextFactory](./imathematicaltextfactory) | 允许创建MathematicalText元素 |
| [IMathFraction](./imathfraction) | 指定分数对象，由分子和分母组成，二者之间用分数线分隔。分数线可以是水平的或对角的，具体取决于分数属性。分数对象也用于表示堆叠函数，将一个元素放在另一个元素上方，无需分数线。 |
| [IMathFractionFactory](./imathfractionfactory) | 允许创建数学分数 |
| [IMathFunction](./imathfunction) | 指定参数的函数。 |
| [IMathFunctionFactory](./imathfunctionfactory) | 允许创建数学函数 |
| [IMathGroupingCharacter](./imathgroupingcharacter) | 指定一个符号，通常在表达式的上方或下方，以突出元素之间的关系 |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory) | 允许创建数学分组字符 |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement) | 指定下标和上标对象，它们位于基部的左侧。 |
| [IMathLimit](./imathlimit) | 指定Limit对象，由基线上的文本和紧接其上方或下方的缩小文本组成。 |
| [IMathLimitFactory](./imathlimitfactory) | 允许创建IMathLimit |
| [IMathMatrix](./imathmatrix) | 指定Matrix对象，由一行或多行和一列中排列的子元素组成。需要注意的是，矩阵没有内置的分隔符。要将矩阵放在括号中，应使用分隔符对象（IMathDelimiter）。可以使用空参数在矩阵中创建间隙。 |
| [IMathMatrixFactory](./imathmatrixfactory) | 允许创建数学矩阵 |
| [IMathNaryOperator](./imathnaryoperator) | 指定N元数学对象，例如求和和积分。它由一个运算符、一个基（或操作数）以及可选的上限和下限组成。N元运算符的示例包括：求和、并集、交集、积分 |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory) | 允许创建IMathNaryOperator |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties) | 指定IMathNaryOperator的属性 |
| [IMathParagraph](./imathparagraph) | 数学段落，作为数学块（IMathBlock）的容器 |
| [IMathParagraphFactory](./imathparagraphfactory) | 允许创建数学段落 |
| [IMathPortion](./imathportion) | 表示包含数学上下文的一部分。 |
| [IMathRadical](./imathradical) | 指定根号功能，由基部和可选角度组成。根号对象的示例为√𝑥。 |
| [IMathRadicalFactory](./imathradicalfactory) | 允许创建数学根号 |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement) | 指定下标和上标对象，它们位于基部的右侧。 |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory) | 允许创建IMathRightSubSuperscriptElementFactory |
| [IMathSubscriptElement](./imathsubscriptelement) | 指定下标对象，由基部和缩小的下标组成，位于下方且偏右。 |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory) | 允许创建IMathSubscriptElement |
| [IMathSuperscriptElement](./imathsuperscriptelement) | 指定上标对象，由基部和缩小的上标组成，位于上方且偏右 |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory) | 允许创建IMathSuperscriptElement |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape) | 分隔符相对于操作数内容的位置和大小 |
| [MathFractionTypes](./mathfractiontypes) | 分数类型 |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument) | 常见的单参数数学函数 |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments) | 常见的双参数数学函数 |
| [MathHorizontalAlignment](./mathhorizontalalignment) | 水平对齐 |
| [MathIntegralTypes](./mathintegraltypes) | 数学积分类型 |
| [MathJustification](./mathjustification) | 指定数学段落的对齐方式（同一段落中相邻的数学文本实例系列） |
| [MathLimitLocations](./mathlimitlocations) | n元运算符中限值的位置（下标/上标）。 |
| [MathNaryOperatorTypes](./mathnaryoperatortypes) | N元运算符IMathNaryOperator的类型（不包括积分） 对于积分 [`MathIntegralTypes`](../aspose.slides.mathtext/mathintegraltypes) |
| [MathRowSpacingRule](./mathrowspacingrule) | 矩阵或数组中列之间的垂直间距类型 |
| [MathSpacingRules](./mathspacingrules) | 矩阵列之间间隔（水平间距）的类型 |
| [MathTopBotPositions](./mathtopbotpositions) | 上下位置枚举 |
| [MathVerticalAlignment](./mathverticalalignment) | 垂直对齐 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->