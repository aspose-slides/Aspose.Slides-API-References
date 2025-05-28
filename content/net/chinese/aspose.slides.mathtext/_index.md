---
title: Aspose.Slides.MathText
second_title: Aspose.Slides for .NET API Reference
description: 包含用于处理 Microsoft PowerPoint 演示中的数学文本的类。
type: docs
weight: 120
url: /zh/aspose.slides.mathtext/
---

包含用于处理 Microsoft PowerPoint 演示中的数学文本的类。

## 类

| 类 | 描述 |
| --- | --- |
| [BaseScript](./basescript) | 数学脚本 |
| [MathAccent](./mathaccent) | 指定由基数和组合的变音符号组成的重音函数 示例: 𝑎́ |
| [MathAccentFactory](./mathaccentfactory) | 允许创建数学重音 |
| [MathArray](./matharray) | 指定方程或任何数学对象的垂直数组 |
| [MathArrayFactory](./matharrayfactory) | 允许创建数学数组 |
| [MathBar](./mathbar) | 指定条形函数，由基数和上横线或下横线组成 |
| [MathBarFactory](./mathbarfactory) | 允许创建数学条形 |
| [MathBlock](./mathblock) | 指定包含在 MathParagraph 内的数学文本实例，并单独在新行开始。所有数学区域，包括方程、表达式、方程或表达式的数组，以及公式都由数学块表示。 |
| [MathBlockFactory](./mathblockfactory) | 允许创建数学块 |
| [MathBorderBox](./mathborderbox) | 在 IMathElement 周围绘制矩形或其他某种边框。 |
| [MathBorderBoxFactory](./mathborderboxfactory) | 允许创建数学边框框 |
| [MathBox](./mathbox) | 指定数学元素的逻辑打包（包装）。例如，一个被框住的对象可以作为带或不带对齐点的操作符仿制器，作为换行点，或被分组以防止其中产生换行。例如，“==”操作符应该被框住以防止换行。 |
| [MathBoxFactory](./mathboxfactory) | 允许创建数学框 |
| [MathDelimiter](./mathdelimiter) | 指定由开闭字符（例如括号、大括号、方括号和竖线）组成的分隔符对象，以及一个或多个数学元素，其中用指定字符分隔。示例: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [MathDelimiterFactory](./mathdelimiterfactory) | 允许创建数学分隔符 |
| [MathElementBase](./mathelementbase) | IMathElement 的基础类，实现所有继承类的某些公共方法，仅供内部使用。继承类必须是 IMathElement。 |
| [MathematicalText](./mathematicaltext) | 数学文本 |
| [MathematicalTextFactory](./mathematicaltextfactory) | 允许创建 MathematicalText 元素 |
| [MathFraction](./mathfraction) | 指定由分子和分母组成的分数对象，两者由分数线分隔。分数线可以是水平或对角线，具体取决于分数的属性。分数对象也用于表示堆叠函数，堆放一个元素在另一个上方，而没有分数线。 |
| [MathFractionFactory](./mathfractionfactory) | 允许创建数学分数 |
| [MathFunction](./mathfunction) | 指定一个参数的函数。 |
| [MathFunctionFactory](./mathfunctionfactory) | 允许创建数学函数 |
| [MathGroupingCharacter](./mathgroupingcharacter) | 指定在表达式上方或下方的分组符号，通常用于突出元素之间的关系 |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory) | 允许创建数学分组字符 |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement) | 指定下标和上标放置在基数左侧的下上标对象。 |
| [MathLimit](./mathlimit) | 指定限制对象，由基线上的文本和其上方或下方的缩小文本组成。 |
| [MathLimitFactory](./mathlimitfactory) | 允许创建 IMathLimit |
| [MathMatrix](./mathmatrix) | 指定矩阵对象，由一行或多行和列中的子元素组成。重要的是，矩阵没有内置的分隔符。要将矩阵放在括号中，应使用分隔符对象 (IMathDelimiter)。可以使用空参数在矩阵中创建空隙。 |
| [MathMatrixFactory](./mathmatrixfactory) | 允许创建数学矩阵 |
| [MathNaryOperator](./mathnaryoperator) | 指定 N 叉数学对象，例如求和和积分。由一个运算符、一个基数（或操作数）和可选的上限和下限组成。N叉运算符的示例包括：求和，联合，交集，积分 |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory) | 允许创建 IMathNaryOperator |
| [MathParagraph](./mathparagraph) | 数学段落，是数学块 (IMathBlock) 的容器 |
| [MathParagraphFactory](./mathparagraphfactory) | 允许创建数学段落 |
| [MathPortion](./mathportion) | 表示内部包含数学上下文的部分。 |
| [MathRadical](./mathradical) | 指定根号函数，由基数和可选的指数组成。根号对象的示例是 √𝑥。 |
| [MathRadicalFactory](./mathradicalfactory) | 允许创建数学根号 |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement) | 指定下标和上标放置在基数右侧的下上标对象。 |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory) | 允许创建 IMathRightSubSuperscriptElementFactory |
| [MathSubscriptElement](./mathsubscriptelement) | 指定下标对象，由基数和放置在其下方和右侧的缩小下标组成。 |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory) | 允许创建 IMathSubscriptElement |
| [MathSuperscriptElement](./mathsuperscriptelement) | 指定上标对象，由基数和放置在其上方和右侧的缩小上标组成。 |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory) | 允许创建 IMathSuperscriptElement |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IMathAccent](./imathaccent) | 指定由基数和组合的变音符号组成的重音函数 示例: 𝑎́ |
| [IMathAccentFactory](./imathaccentfactory) | 允许创建数学重音 |
| [IMathArray](./imatharray) | 指定方程或任何数学对象的垂直数组 |
| [IMathArrayFactory](./imatharrayfactory) | 允许创建数学数组 |
| [IMathBar](./imathbar) | 指定条形函数，由基数和上横线或下横线组成 |
| [IMathBarFactory](./imathbarfactory) | 允许创建数学条形 |
| [IMathBlock](./imathblock) | 指定包含在 MathParagraph 内的数学文本实例，并单独在新行开始。所有数学区域，包括方程、表达式、方程或表达式的数组，以及公式都由数学块表示。 |
| [IMathBlockCollection](./imathblockcollection) | 数学块的集合 (IMathBlock) |
| [IMathBlockFactory](./imathblockfactory) | 允许创建数学块 |
| [IMathBorderBox](./imathborderbox) | 在 IMathElement 周围绘制矩形或其他某种边框。 |
| [IMathBorderBoxFactory](./imathborderboxfactory) | 允许创建数学边框框 |
| [IMathBox](./imathbox) | 指定数学元素的逻辑打包（包装）。例如，一个被框住的对象可以作为带或不带对齐点的操作符仿制器，作为换行点，或被分组以防止其中产生换行。例如，“==”操作符应该被框住以防止换行。 |
| [IMathBoxFactory](./imathboxfactory) | 允许创建数学框 |
| [IMathDelimiter](./imathdelimiter) | 指定由开闭字符（例如括号、大括号、方括号和竖线）组成的分隔符对象，以及一个或多个数学元素，其中用指定字符分隔。示例: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [IMathDelimiterFactory](./imathdelimiterfactory) | 允许创建数学分隔符 |
| [IMathElement](./imathelement) | 所有数学元素的基础接口：分数、数学文本、函数、多个元素的表达式等 |
| [IMathElementCollection](./imathelementcollection) | 表示数学元素 (MathElement) 的集合。 |
| [IMathematicalText](./imathematicaltext) | 数学文本 |
| [IMathematicalTextFactory](./imathematicaltextfactory) | 允许创建 MathematicalText 元素 |
| [IMathFraction](./imathfraction) | 指定由分子和分母组成的分数对象，两者由分数线分隔。分数线可以是水平或对角线，具体取决于分数的属性。分数对象也用于表示堆叠函数，堆放一个元素在另一个上方，而没有分数线。 |
| [IMathFractionFactory](./imathfractionfactory) | 允许创建数学分数 |
| [IMathFunction](./imathfunction) | 指定一个参数的函数。 |
| [IMathFunctionFactory](./imathfunctionfactory) | 允许创建数学函数 |
| [IMathGroupingCharacter](./imathgroupingcharacter) | 指定在表达式上方或下方的分组符号，通常用于突出元素之间的关系 |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory) | 允许创建数学分组字符 |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement) | 指定下上标对象，基数及其左侧的下标和上标。 |
| [IMathLimit](./imathlimit) | 指定限制对象，由基线上的文本和其上方或下方的缩小文本组成。 |
| [IMathLimitFactory](./imathlimitfactory) | 允许创建 IMathLimit |
| [IMathMatrix](./imathmatrix) | 指定矩阵对象，由一行或多行和列中的子元素组成。重要的是，矩阵没有内置的分隔符。要将矩阵放在括号中，应使用分隔符对象 (IMathDelimiter)。可以使用空参数在矩阵中创建空隙。 |
| [IMathMatrixFactory](./imathmatrixfactory) | 允许创建数学矩阵 |
| [IMathNaryOperator](./imathnaryoperator) | 指定 N 叉数学对象，例如求和和积分。由一个运算符、一个基数（或操作数）和可选的上限和下限组成。N叉运算符的示例包括：求和，联合，交集，积分 |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory) | 允许创建 IMathNaryOperator |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties) | 指定 IMathNaryOperator 的属性 |
| [IMathParagraph](./imathparagraph) | 数学段落，是数学块 (IMathBlock) 的容器 |
| [IMathParagraphFactory](./imathparagraphfactory) | 允许创建数学段落 |
| [IMathPortion](./imathportion) | 表示内部包含数学上下文的部分。 |
| [IMathRadical](./imathradical) | 指定根号函数，由基数和可选的指数组成。根号对象的示例是 √𝑥。 |
| [IMathRadicalFactory](./imathradicalfactory) | 允许创建数学根号 |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement) | 指定下上标对象，基数及其右侧的下标和上标。 |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory) | 允许创建 IMathRightSubSuperscriptElementFactory |
| [IMathSubscriptElement](./imathsubscriptelement) | 指定下标对象，由基数和放置在其下方和右侧的缩小下标组成。 |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory) | 允许创建 IMathSubscriptElement |
| [IMathSuperscriptElement](./imathsuperscriptelement) | 指定上标对象，由基数和放置在其上方和右侧的缩小上标组成。 |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory) | 允许创建 IMathSuperscriptElement |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape) | 分隔符相对于操作数内容的位置和大小 |
| [MathFractionTypes](./mathfractiontypes) | 分数类型 |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument) | 常见的单参数数学函数 |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments) | 常见的双参数数学函数 |
| [MathHorizontalAlignment](./mathhorizontalalignment) | 水平对齐 |
| [MathIntegralTypes](./mathintegraltypes) | 数学积分类型 |
| [MathJustification](./mathjustification) | 指定数学段落的对齐（同一段落中多个数学文本实例的系列相邻） |
| [MathLimitLocations](./mathlimitlocations) | n 叉运算符中的限制（下标/上标）位置 |
| [MathNaryOperatorTypes](./mathnaryoperatortypes) | N 叉运算符 IMathNaryOperator 类型（不包括积分） 对于积分 [`MathIntegralTypes`](../aspose.slides.mathtext/mathintegraltypes) |
| [MathRowSpacingRule](./mathrowspacingrule) | 矩阵或数组中列间的垂直间距类型 |
| [MathSpacingRules](./mathspacingrules) | 矩阵列之间的间隔类型（水平间隔） |
| [MathTopBotPositions](./mathtopbotpositions) | 上下位置枚举 |
| [MathVerticalAlignment](./mathverticalalignment) | 垂直对齐 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->