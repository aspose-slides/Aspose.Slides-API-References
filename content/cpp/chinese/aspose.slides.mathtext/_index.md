---
title: "Aspose::Slides::MathText"
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 157
url: /zh/aspose.slides.mathtext/
---
## 类

| 类 | 描述 |
| --- | --- |
| [BaseScript](./basescript/) | 数学脚本 |
| [IHasControlCharacterProperties](./ihascontrolcharacterproperties/) | [IMathElement](./imathelement/) 与 [Control](../aspose.slides/control/) 字符属性 |
| [IMathAccent](./imathaccent/) | 指定重音函数，由基字符和组合变音符组成 示例：\\uD835\\uDC4E\\u0301 |
| [IMathAccentFactory](./imathaccentfactory/) | 允许创建数学重音 |
| [IMathArray](./imatharray/) | 指定垂直排列的方程或任何数学对象 |
| [IMathArrayFactory](./imatharrayfactory/) | 允许创建数学数组 |
| [IMathBar](./imathbar/) | 指定条形函数，由基参数和上划线或下划线组成 |
| [IMathBarFactory](./imathbarfactory/) | 允许创建数学条形 |
| [IMathBlock](./imathblock/) | 指定包含在 [MathParagraph](./mathparagraph/) 中且单独起始行的数学文本实例。所有数学区域，包括方程、表达式、方程或表达式数组以及公式，都由数学块表示。 |
| [IMathBlockCollection](./imathblockcollection/) | 数学块的集合 ([IMathBlock](./imathblock/)) |
| [IMathBlockFactory](./imathblockfactory/) | 允许创建数学块 |
| [IMathBorderBox](./imathborderbox/) | 在 [IMathElement](./imathelement/) 周围绘制矩形或其他边框。 |
| [IMathBorderBoxFactory](./imathborderboxfactory/) | 允许创建数学边框盒 |
| [IMathBox](./imathbox/) | 指定数学元素的逻辑框装（包装）。例如，盒装对象可以作为带或不带对齐点的运算符仿真器，充当换行点，或者被分组以防止内部换行。例如，"==" 运算符应进行盒装以防止换行。 |
| [IMathBoxFactory](./imathboxfactory/) | 允许创建数学盒 |
| [IMathDelimiter](./imathdelimiter/) | 指定定界符对象，由开闭字符（如圆括号、大括号、方括号和竖线）组成，内部包含一个或多个数学元素，以指定字符分隔。示例：(\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [IMathDelimiterFactory](./imathdelimiterfactory/) | 允许创建数学定界符 |
| [IMathElement](./imathelement/) | 任何数学元素的基础接口：分数、数学文本、函数、包含多个元素的表达式等 |
| [IMathElementCollection](./imathelementcollection/) | 表示数学元素的集合 (MathElement)。 |
| [IMathematicalText](./imathematicaltext/) | 数学文本 |
| [IMathematicalTextFactory](./imathematicaltextfactory/) | 允许创建 [MathematicalText](./mathematicaltext/) 元素 |
| [IMathFraction](./imathfraction/) | 指定分数对象，由分子和分母通过分数线分隔。分数线可水平或对角，根据分数属性而定。该分数对象也用于表示堆叠函数，将一个元素置于另一个元素之上，无分数线。 |
| [IMathFractionFactory](./imathfractionfactory/) | 允许创建数学分数 |
| [IMathFunction](./imathfunction/) | 指定参数函数。 |
| [IMathFunctionFactory](./imathfunctionfactory/) | 允许创建数学函数 |
| [IMathGroupingCharacter](./imathgroupingcharacter/) | 指定表达式上方或下方的分组符号，通常用于突出元素之间的关系 |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory/) | 允许创建数学分组字符 |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement/) | 指定上下标对象，由基字符以及放置在基左侧的下标和上标组成。 |
| [IMathLimit](./imathlimit/) | 指定极限对象，由基线上的文本以及紧邻其上方或下方的缩小文本组成。 |
| [IMathLimitFactory](./imathlimitfactory/) | 允许创建 [IMathLimit](./imathlimit/) |
| [IMathMatrix](./imathmatrix/) | 指定矩阵对象，由子元素排布成一行或多行多列。需要注意矩阵本身不带内置定界符。若要在括号中放置矩阵，应使用定界符对象 ([IMathDelimiter](./imathdelimiter/))。可以使用空参数在矩阵中创建空位。 |
| [IMathMatrixFactory](./imathmatrixfactory/) | 允许创建数学矩阵 |
| [IMathNaryOperator](./imathnaryoperator/) | 指定 N 元数学对象，如求和与积分。它由运算符、基（或操作数）以及可选的上、下限组成。N 元运算符示例：求和、并集、交集、积分 |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory/) | 允许创建 [IMathNaryOperator](./imathnaryoperator/) |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties/) | 指定 [IMathNaryOperator](./imathnaryoperator/) 的属性 |
| [IMathParagraph](./imathparagraph/) | 包含数学块 ([IMathBlock](./imathblock/)) 的数学段落 |
| [IMathParagraphFactory](./imathparagraphfactory/) | 允许创建数学段落 |
| [IMathPhantom](./imathphantom/) | 表示幽灵数学对象 (<m:phant>)，它影响子元素的布局但不一定显示。幽灵可以隐藏基表达式，同时保留其宽度、高度或深度以对齐公式或预留空间。可见性和几何行为由属性如 Show、ZeroWid、ZeroAsc、ZeroDesc、Transp 控制。 |
| [IMathPortion](./imathportion/) | 表示内部带有数学上下文的部分。 |
| [IMathRadical](./imathradical/) | 指定根函数，由基和可选的指数组成。根对象示例为 \\u221A\\uD835\\uDC65。 |
| [IMathRadicalFactory](./imathradicalfactory/) | 允许创建数学根号 |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement/) | 指定上下标对象，由基字符以及放置在基右侧的下标和上标组成。 |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) | 允许创建 [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [IMathSubscriptElement](./imathsubscriptelement/) | 指定下标对象，由基字符以及放置在右下方的缩小下标组成。 |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory/) | 允许创建 [IMathSubscriptElement](./imathsubscriptelement/) |
| [IMathSuperscriptElement](./imathsuperscriptelement/) | 指定上标对象，由基字符以及放置在右上方的缩小上标组成 |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory/) | 允许创建 [IMathSuperscriptElement](./imathsuperscriptelement/) |
| [MathAccent](./mathaccent/) | 指定重音函数，由基字符和组合变音符组成 示例：\\uD835\\uDC4E\\u0301 |
| [MathAccentFactory](./mathaccentfactory/) | 允许创建数学重音 |
| [MathArray](./matharray/) | 指定垂直排列的方程或任何数学对象 |
| [MathArrayFactory](./matharrayfactory/) | 允许创建数学数组 |
| [MathBar](./mathbar/) | 指定条形函数，由基参数和上划线或下划线组成 |
| [MathBarFactory](./mathbarfactory/) | 允许创建数学条形 |
| [MathBlock](./mathblock/) | 指定包含在 [MathParagraph](./mathparagraph/) 中且单独起始行的数学文本实例。所有数学区域，包括方程、表达式、方程或表达式数组以及公式，都由数学块表示。 |
| [MathBlockFactory](./mathblockfactory/) | 允许创建数学块 |
| [MathBorderBox](./mathborderbox/) | 在 [IMathElement](./imathelement/) 周围绘制矩形或其他边框。 |
| [MathBorderBoxFactory](./mathborderboxfactory/) | 允许创建数学边框盒 |
| [MathBox](./mathbox/) | 指定数学元素的逻辑框装（包装）。例如，盒装对象可以作为带或不带对齐点的运算符仿真器，充当换行点，或者被分组以防止内部换行。例如，"==" 运算符应进行盒装以防止换行。 |
| [MathBoxFactory](./mathboxfactory/) | 允许创建数学盒 |
| [MathDelimiter](./mathdelimiter/) | 指定定界符对象，由开闭字符（如圆括号、大括号、方括号和竖线）组成，内部包含一个或多个数学元素，以指定字符分隔。示例：(\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [MathDelimiterFactory](./mathdelimiterfactory/) | 允许创建数学定界符 |
| [MathElementBase](./mathelementbase/) | [IMathElement](./imathelement/) 的基类，实现了一些所有派生类共有的方法。仅供内部使用。派生类必须是 [IMathElement](./imathelement/)。 |
| [MathematicalText](./mathematicaltext/) | 数学文本 |
| [MathematicalTextFactory](./mathematicaltextfactory/) | 允许创建 [MathematicalText](./mathematicaltext/) 元素 |
| [MathFraction](./mathfraction/) | 指定分数对象，由分子和分母通过分数线分隔。分数线可水平或对角，根据分数属性而定。该分数对象也用于表示堆叠函数，将一个元素置于另一个元素之上，无分数线。 |
| [MathFractionFactory](./mathfractionfactory/) | 允许创建数学分数 |
| [MathFunction](./mathfunction/) | 指定参数函数。 |
| [MathFunctionFactory](./mathfunctionfactory/) | 允许创建数学函数 |
| [MathGroupingCharacter](./mathgroupingcharacter/) | 指定表达式上方或下方的分组符号，通常用于突出元素之间的关系 |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory/) | 允许创建数学分组字符 |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement/) | 指定上下标对象，由基字符以及放置在基左侧的下标和上标组成。 |
| [MathLimit](./mathlimit/) | 指定极限对象，由基线上的文本以及紧邻其上方或下方的缩小文本组成。 |
| [MathLimitFactory](./mathlimitfactory/) | 允许创建 [IMathLimit](./imathlimit/) |
| [MathMatrix](./mathmatrix/) | 指定矩阵对象，由子元素排布成一行或多行多列。需要注意矩阵本身不带内置定界符。若要在括号中放置矩阵，应使用定界符对象 ([IMathDelimiter](./imathdelimiter/))。可以使用空参数在矩阵中创建空位。 |
| [MathMatrixFactory](./mathmatrixfactory/) | 允许创建数学矩阵 |
| [MathNaryOperator](./mathnaryoperator/) | 指定 N 元数学对象，如求和与积分。它由运算符、基（或操作数）以及可选的上、下限组成。N 元运算符示例：求和、并集、交集、积分 |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory/) | 允许创建 [IMathNaryOperator](./imathnaryoperator/) |
| [MathParagraph](./mathparagraph/) | 包含数学块 ([IMathBlock](./imathblock/)) 的数学段落 |
| [MathParagraphFactory](./mathparagraphfactory/) | 允许创建数学段落 |
| [MathPhantom](./mathphantom/) | 表示幽灵数学对象 (<m:phant>)，它影响子元素的布局但不一定显示。幽灵可以隐藏基表达式，同时保留其宽度、高度或深度以对齐公式或预留空间。可见性和几何行为由属性如 Show、ZeroWid、ZeroAsc、ZeroDesc、Transp 控制。 |
| [MathPortion](./mathportion/) | 表示内部带有数学上下文的部分。 |
| [MathRadical](./mathradical/) | 指定根函数，由基和可选的指数组成。根对象示例为 \\u221A\\uD835\\uDC65。 |
| [MathRadicalFactory](./mathradicalfactory/) | 允许创建数学根号 |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement/) | 指定上下标对象，由基字符以及放置在基右侧的下标和上标组成。 |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory/) | 允许创建 [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [MathSubscriptElement](./mathsubscriptelement/) | 指定下标对象，由基字符以及放置在右下方的缩小下标组成。 |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory/) | 允许创建 [IMathSubscriptElement](./imathsubscriptelement/) |
| [MathSuperscriptElement](./mathsuperscriptelement/) | 指定上标对象，由基字符以及放置在右上方的缩小上标组成 |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory/) | 允许创建 [IMathSuperscriptElement](./imathsuperscriptelement/) |

## 枚举

| 枚举 | 描述 |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape/) | 定界符相对于操作数内容的位置和大小 |
| [MathFractionTypes](./mathfractiontypes/) | 分数类型 |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument/) | 单参数常用数学函数 |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments/) | 双参数常用数学函数 |
| [MathHorizontalAlignment](./mathhorizontalalignment/) | 水平对齐 |
| [MathIntegralTypes](./mathintegraltypes/) | 数学积分类型 |
| [MathJustification](./mathjustification/) | 指定数学段落的对齐方式（同一段落中相邻的数学文本实例系列） |
| [MathLimitLocations](./mathlimitlocations/) | n 元运算符中极限（下标/上标）的位置。 |
| [MathNaryOperatorTypes](./mathnaryoperatortypes/) | n 元运算符 [IMathNaryOperator](./imathnaryoperator/) 类型（不包括积分），积分使用 [MathIntegralTypes](./mathintegraltypes/) |
| [MathRowSpacingRule](./mathrowspacingrule/) | 矩阵或数组中列之间的垂直间距类型 |
| [MathSpacingRules](./mathspacingrules/) | 矩阵列之间的间隙（水平间距）类型 |
| [MathTopBotPositions](./mathtopbotpositions/) | 顶部/底部位置枚举 |
| [MathVerticalAlignment](./mathverticalalignment/) | 垂直对齐 |